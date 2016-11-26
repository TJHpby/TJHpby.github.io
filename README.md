# HTML基本介绍和解释 

##1.html预备知识
+ html 是一种**标记语言**,而非**编程语言**,它是一种超文本标记语言
+ html 由一套**标记标签**组成，换言之**标记语言**由**标记标签**组成  

>标记标签
+ **HTML 标签**是由尖括号包围的关键词，比如   \<html> .
+ **HTML 标签**通常是成对出现的，比如  \<b> 和 \</b>，在该标签对中的第一个标签是开始标签(开放标签)，第二个标签是结束标签(闭合标签) .  

>html文档
+ **html文档** 由 ***文本*** 和 ***html标签*** 组成.
+ **html文档** 由称为 **网页**


##2.html的基本标签
* HTML 标题（Heading）是通过 \<h1> - \<h6> 等标签进行标记的,从h1到h6分别代表不同的标题等级（从大到小）.  

        <h1>This is a heading</h1>
* HTML 段落（paragraph）是通过 \<p> 标签标记的 .

        <p>This is a paragraph</p>
* HTML 链接（link）是通过 \<a> 标签标记的 .

        <a href="http://thwiki.cc/">This is a link</a>
>herf为该标签的**属性**，后续会提到
* HTML 图像（image）是通过 \<img> 标签标记的 .

        <img src="w3school.jpg" width="104" height="142" />
>通过其属性可以确定图片的大小、高宽   
* HTML 注释通过 \<!--> 标签标记

        <!-- This is a comment -->
* html通过\<hr /> 标签在 HTML 页面中创建水平线

        <p>This is a paragraph</p>
        <hr />        //作出水平线分隔
        <p>This is a paragraph</p>
* html通过\<br /> 标签在 HTML 页面进行换行

        <p>This is <hr /> a paragraph</p>      //在不产生新段落的情况下换行


##3.html的元素
* **HTML 元素**指的是从**开始标签（start tag）**到**结束标签（end tag）**的所有代码 .    
* 元素的**内容**是开始标签与结束标签**之间**的内容 .
* HTML 元素可以互相**嵌套** .
* 大多数 HTML 元素可拥有**属性** .
* 某些 HTML 元素具有**空内容**（empty content）,空元素会在**开始标签中**进行关闭（以开始标签的结束而结束） .



>例子：
* \<p>元素

        <p>this is a paragraph</p>        //该代码表示一个<p>元素
这个 \<p> 元素定义了 HTML 文档中的一个段落。  
这个元素拥有一个开始标签 \<p>，以及一个结束标签 \</p> .  
元素内容是：This is my first paragraph .  

>空的 HTML 元素
* **没有内容**的 HTML 元素被称为**空元素**。例： \<br> 就是没有关闭标签的空元素（\<br> 标签定义换行）.   
* 空元素是在**开始标签**中关闭的。  
* 在**开始标签**中添加**斜杠**，比如 \<br />，是关闭空元素的正确方法。   


>关于html的元素可以参阅以下网站：  
[http://www.w3school.com.cn/tags/html_ref_byfunc.asp](http://www.w3school.com.cn/tags/html_ref_byfunc.asp)
 
        
##4.html的属性
* html标签可拥有**属性**，**属性**为**元素**提供更多**信息**。
* 属性总是以**名称/值**对的形式出现，比如：name="value"。
* 属性总是在 HTML 元素的**开始标签**中定义的。
        
>**格式：**    
"属性名称" = "属性值"
  
>**例子：**  

         <body bgcolor="yellow">      //<body> 定义 HTML 文档的主体，'bgcolor="yellow"'使该元素拥有关于背景颜色的附加信息。
         
**注意:**  
* 属性值应该始终被包括在**引号内**。 **双引号**是最常用的，不过使用**单引号**也没有问题。  
* 在某些个别的情况下，比如**属性值本身**就含有**双引号**(例如该属性值包含文本内容），那么您**必须**使用**单引号**  

        name='Bill "HelloWorld" Gates'     //文本内容为Bill "HelloWorld" Gates，包含了双引号，就必须用单引号引用为属性值  
  
>关于html的全局属性可以参阅以下网站：  
[http://www.w3school.com.cn/tags/html_ref_standardattributes.asp](http://www.w3school.com.cn/tags/html_ref_standardattributes.asp)  

##5.html样式
* style 属性提供了一种改变所有 HTML 元素的样式的通用方法.  

>样式的实例： 
>>1.背景颜色

        <h2 style="background-color:red">This is a heading</h2>       //文字的背景颜色变为红色
>>2.文本的字体、颜色和尺寸

        <p style="font-family:arial;color:red;font-size:20px;">A paragraph.</p>             
>>3.文本对齐

        <h1 style="text-align:center">This is a heading</h1>


>详细的样式应该用css文件（样式表）定义，具体css学习见：   
[http://www.w3school.com.cn/css/index.asp](http://www.w3school.com.cn/css/index.asp)

##6.html的型式化
* HTML 定义了很多供型式化输出的元素以供使用  
* 用以型式化的元素可以分为三类：    

>1.直接型式化                                            
[http://www.w3school.com.cn/html/html_formatting.asp](http://www.w3school.com.cn/html/html_formatting.asp)                         
2.'计算机输出'型式化                                
[http://www.w3school.com.cn/html/html_computercode_elements.asp](http://www.w3school.com.cn/html/html_computercode_elements.asp)          
3.'引用和术语定义'型式化                                         
[http://www.w3school.com.cn/html/html_quotation_elements.asp](http://www.w3school.com.cn/html/html_quotation_elements.asp)                    


 

