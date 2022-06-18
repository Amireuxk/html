HTML：
Hyper Text Markup Language(超文本标记语言)

<hr><hr/>；意为用/关闭空元素
utf-8 国际编码 包含中文

页面间链接：
页面与页面之间的跳转

锚链接：
从A页面的X位置跳转到本页或B页面中的Y位置

创建一个超链接N

创建一个标记or内容   命名为N

src与href的区别：
不同标签使用src与href引用当前网页之外的资源，主要区别如下
#src(source)的值是外部资源的访问路径，在请求src资源时会将其只想的资源下载并应用到当前文档中，次外外部资源作为当前文档的一部分(引入)，一般用作非文本引入方式
#href表示超文本引用，在使用href请求外部资源时，会下载外部资源，同时当前网页读取外部资源的内容(引用)。一般用作文本引入方式

块元素：无论多少内容，改元素独占一行(p、h1-h6...) (会自动换行)
行内元素：(不会自动换行)






<table>  表格标签
<tr> 行标签
<td>单元格标签
<td colspan="n">   colspan所跨的行数
<td rowspan="n">  rowspan所跨的行数
<video src="视频路径" controls></video>  src指定路径  controls 提供播放等控件
auotoplay 自动播放
loop循环播放

结构化语义标签：
header：标题头部区域内容
footer：标记脚部区域的内容
section：web页面中的一块独立区域
artucle：独立的文章内容
aside：相关内容或应用
nav：导航类辅助内容
例： <header><h2>网页头部</h2></header>

内联框架
<iframe src="path" > </iframe>


表单元素：
语法：
<form method="post" action="result.html">
<p> 名字: <input name="name" type="text"> </p>
<p> 密码: <input name="pass" type="password"> </p>

type:指定元素的类型 如：text、password、CheckBox、radio、submit、reset、file、hidden、image和button，默认text
name:指定表格元素的名称
value:元素的初始值。type为radio时必须指定一个值
size:指定变淡元素的初始宽度。当type为text或password时，表单元素的大小以字符为单位。对于其他类型，宽度以像素为单位
maxlength:type为text或password时，输入的最大字符数
checked:type为radio或CheckBox时，指定按钮是否是被选中

文本框
<input type="text" >

disabled 禁用


表单验证(减轻服务器压力)
placeholder
required

正则表达式
pattern 验证规则，正则表达式