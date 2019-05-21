## A New Post

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
HTML（Hypertext Markup Language） 超文本标记语言  结构
CSS（Cascading Style Sheets） 层叠样式表  样式
JS（JavaScript） 脚本语言  行为、动作


## 一、HTML
用标签（标记）来描述网页的语言
用一对一对的标签对组成的。
或者自闭合标签（空标签）。
成对出现的标签，前面的叫开始标签，后面的叫结束标签。
可以给文本附上不同的语义

## 二、常用标签
1．H1标签  主标题（一级标题）
2．H2标签  二级标题  h3 h4 h5 h6
3．P 标签  段落
4．Div 标签  没有任何语义，可以把它看成一个块或者一个盒子
5．Strong 可以文字加粗，有强调的意义，对seo（搜索引擎优化）有帮助
6．b  可以让文字加粗 
7．Em  可以让文字倾斜，有强调的意义，对seo（搜索引擎优化）有帮助
8．i 可以让文字倾斜
9．Ul li
无序列表
Ul和li是固定嵌套
Ul是li的父元素
Li是ul的子元素
Ul的直接子元素必须是li，li里可以嵌套其他元素
Li的父元素必须是ul或ol
10．Ol li  
有序列表
Ol和li固定嵌套
Ol 是li 的父元素
Li是ol的子元素
Ol里面的直接子元素必须是li，li里面可以嵌套其他元素

11．Dl dt dd
定义列表
Dl是dt和dd的父元素
Dt和dd 是兄弟元素
Dl里面只能放dt和dd
Dt和dd里面可以放其他内容
Dt相当于小标题 dd相当于列表项
Dd是对dt的解释和说明
12．Span
没有任何语义
13．Img 图片 自闭和标签
<img src="nigulasizhaosi.png" alt="社会你四哥" title="尼古拉斯赵四" width="100" height="100">
Src 图片路径
Alt 图片描述（当图片路径出现问题，或者图片加载不出来的时候会显示）
Title  图片标题（鼠标放上去的时候会显示）
width="100" 宽度 
height="100" 高度


14.br 强制换行 自闭和标签

## 三、Html页面的基本结构
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title></title>
</head>
<body>
</body>
</html>

1.<!DOCTYPE html>  
声明文档
告诉浏览器的解析器用那种规范来解析该文档

2.<html> html中所有的内容都放到html标签里

3.<head> 页面的头部
里面包含页面的头部信息
<meta charset="UTF-8">
常用的编码格式：UTF-8  gbk(国标扩)  gb2312(国标2312)
<title> 页面的标题
页面的最上面显示
用户收藏夹里面的标题显示title标签里面的内容


4.<body> 页面的主体
页面中显示的内容都放到body标签里面
四、注释
1．Html  <!--注释内容-->
2．Css   /* 注释内容 */
3．Js  
单行
//注释内容
多行
/* 注释内容
注释内容
注释内容*/

五、浏览器及内核


六、常用标签
1.块标签（块元素）
单独占一行
如果不设置宽度，宽度默认是一整行
可以设置所有样式
H1  h2  h3  h4  h5  h6  p ul  li  ol  dl dt  dd
2.内联标签（行内标签、行内元素、内联元素）
在同一行显示
宽度和高度由内内容撑开
不可以设置所有样式（宽度和高度等）
Strong b em i  span
3.内联块标签（行内块标签、行内块元素）
既有块元素特点又有内联元素特点
在同一行显示
可以设置宽度和高度
img

七、了解样式
内部样式：写到html页面里的head标签里
在head标签里写style标签
语法：
选择器{
声明;
声明;
声明。。。。。
}
声明：
属性名：属性值

声明与声明中间用分号隔开
属性名与属性值中间用冒号隔开

宽度 width  单位：px
高度 height 单位：px
背景颜色 background-color

八、
Html里面对空格和回车不敏感，打一个空格和一堆空格效果是一样的，打一个回车和打一堆回车效果是一样的。
写一个&nbsp; 就可以表示一个空格

九、路径
1.绝对路径：从盘符开始，具体的链接
2.相对路径
（1）当前文件和被引入的文件在同一个文件夹里：
./被引入文件的名（包括拓展名）  ./可以省略不写
（2）被引入的文件在当前文件的下一级
被引入文件所在文件夹的名字/被引入文件的文件名


（3）被引入的文件在当前文件的上一级
../被引入文件的文件名




## 十、
Html的语义是什么：
根据页面的结构，使用合理语义的标签，比如段落用p，主标题用h1...

好处：
1.便于后期维护
2.对seo有帮助
3.对用户体验好
4.当没有css的时候，也能很好的呈现页面的内容结构