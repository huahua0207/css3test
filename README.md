# css3test

> 学习css3时的笔记。

---------------------------------------

## css3选择器

1.   css3后代选择器
     .list li:only-child
     选中在list中作为唯一的li子元素存在<br>

     .list :only-child
     选中list中的只有一个唯一一个子元素的 元素
     -----------------------------------------------


3.伪类选择器
   
    - :focus    匹配获得焦点的input元素
    - :first-letter    匹配p标签的第一个文字
    - :first-line      匹配p标签的第一行文字
    - :before			在每个<p>标签内容之前插入内容(添加的是行内标签)
    - :after			在每个<p>标签内容之后插入内容(添加的是行内标签)

> :before、:after  功能
> 1. 清除浮动
```css
.clf:after,.clf:before{
	content:""; //必须得有
	display:block;
	clear:both;
}
```

> 2. 做一些常用效果 “”  图标


4.属性选择器
- [attr] 选中带有指定属性的元素
- [attr=value] 选中带有指定属性和值的元素  //value值不用加引号
- [attribute~=value]  //匹配的时候是一个词  不是一个字母
- [attribute|=value]
- [attribute^=value]
- [href^=value] //ftp 文件传输协议  http 超文本传输协议  https安全传输   mailto邮箱   


