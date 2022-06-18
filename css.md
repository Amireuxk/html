css：层叠样式表；级联样式表
基本语法结构：
选择器 {声明1；
	声明2；
	...}
例：
h1{
	font-size;12px;
	color:#F00;
}

行内样式：<h1 style="color:red;">xxxxxx</h1>

内部样式表：
在head中间的style标签中

外部样式表：
保存在扩展名为.css的样式表中

链接式与导入式的区别：
<link/>标签属于XHTML，@inport是属于CSS2.1
使用<link/>链接的CSS文件先加载到网页当中，在进行编译显示
@import是属于CSS2.1特有的，对不兼容CSS2.1的浏览器是无效的


行内样式>内部样式>外部样式     (就近原则)

基本选择器
<h1>...<h6>、<p>、<img/>
类选择器
.class{xxxxx}  (.class类名称)
<标签名 class="类名称">标签内容</标签名>

ID选择器
#id {font-size:16px;}  唯一的

ID选择器>类选择器>标签选择器
