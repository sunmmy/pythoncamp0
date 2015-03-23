# markdown 教程

##markdown是什么?

根据维基百科的解释

> Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。

**标记语言**是什么？让我们回到最传统的出版流程中，有一名工作人员，他专门负责在出版样稿中标注文本的格式，比如这一行是一号标题，那一段是引用的格式等等。这个工作人员就称为[“mark-up men”](http://pub310.pressbooks.com/chapter/3-1-markup-languages-proving-why-you-should-know-html/) 
他使用特定符号来标明某段文字的排印出来的效果，这样的符号其实就是标记语言。在传统出版流程中，这些标记语言被文字输入人员（刻版人员）识别后在制版中使用，而在数字时代，则需要让计算机程序识别出来，从而呈现
在读者眼前。

正如传统出版流程中不同出版商可能使用不同的约定俗成的标记方式一样，数字时代的标记语言也有多种，比较著名的有html、xml等，我们今天要介绍的Markdown是一种**轻量级**ß的标记语言。轻量级我们可以通过html与Markdown
的两段代码来理解。

###html
    <html>
    <head>
      <meta content='application/xhtml+xml;charset=utf-8' http-equiv='Content-type' />
    <title>Markdown </title>
    </head>
    <body>
      <h1 id='id1'>Markdown </h1>

      <p><strong>Markdown </strong> 是一种 <em>轻量级</em> 的标记语言。</p>

     <ul>
     <li>可以使用最简单的文本编辑器编辑。</li>
     <li>所见即所得，非技术控亦可直接阅读源码。</li>
   
    </ul>
    <body>
    </html>
    
### Markdown
    ###Markdown

    **Markdown** 是一种 *轻量级* 的标记语言。

    - 可以使用最简单的文本编辑器编辑。
    - 所见即所得，非技术控亦可直接阅读源码。

这个例子可以看出，在同一种输出效果后，Markdown所要标记的东西比html少了很多，也更容易被直接阅读，因此称之为轻量级。同时，Markdown的内容能够转换成html文档。

## Markdown的好处

## markdown语法细则

## markdown的软件选择和调教





##参考资料

http://zh.wikipedia.org/zh/Markdown
http://www.worldhello.net/gotgithub/appendix/markups.html