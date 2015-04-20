# Markdown 教程

##Markdown是什么?

根据维基百科的解释

> Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。

**标记语言**是什么？让我们回到最传统的出版流程中，有一名工作人员，他专门负责在出版样稿中标注文本的格式，比如这一行是一号标题，那一段是引用的格式等等。这个工作人员就称为[“mark-up men”](http://pub310.pressbooks.com/chapter/3-1-markup-languages-proving-why-you-should-know-html/) 
他使用特定符号来标明某段文字的排印出来的效果，这样的符号其实就是标记语言。在传统出版流程中，这些标记语言被文字输入人员（刻版人员）识别后在制版中使用，而在数字时代，则需要让计算机程序识别出来，从而呈现在读者眼前。

正如传统出版流程中不同出版商可能使用不同的约定俗成的标记方式一样，数字时代的标记语言也有多种，比较著名的有html、xml等，我们今天要介绍的Markdown是一种**轻量级**的标记语言。轻量级我们可以通过html与Markdown
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

这个例子可以看出，在输出同一种效果时，Markdown所要标记的东西比html少了很多，也更容易被直接阅读，因此称之为轻量级。同时，Markdown的内容能够转换成html文档。

## Markdown的好处

了解了Markdown是什么之后，就会有人疑惑，为什么要用这样语言。对于大多数人来说，已经习惯的是在Word上用鼠标选择后再点击各种格式效果，为什么要自己手动添加格式的标记呢？

* 专注内容

专注于内容是我最欣赏Markdown的方面，打开一个Markdown文本，只需要按照自己思路顺畅写下去就好，不用考虑这里要选择一下成为一级标题，那里需要选择然后加粗。不用被Word/Pages
繁重的功能困扰，因为写作本身最核心的就是写下去，而不是关注格式。这种能够顺畅写作的体验，一定要尝试几次用Markdown写才能体会。开始时可能觉得不习惯，甚至觉得没有原来的方便（事实上
笔者一年前尝试过一两次就放弃了，但是最近拾起来后发现简直是神器），尤其在有一大堆书写任务时，这种体验尤为重要。

* 兼容

由于使用的是Mac Os，文本格式问题成为很大的困扰，Pages的保存格式其他电脑打不开，转成DOC的格式各种渣。而Markdown就是纯文本txt格式，任何平台都能打开。同时，借助专门的Markdown应用
可以方便的转化成PDF（发送给别人）以及html（邮件里使用）等，解决兼容问题。




## Markdown语法细则
看到这些好处是不是想尝试了，不同于其他的语言，Markdown语法非常简单，几乎就是小学语文学习修改符号的难度。

**Are You Ready?**

### 1. 标题
	#一级标题
	##二级标题
	###三级标题
	####四级标题
你猜六级标题是啥？

	######六级标题	
	
输出效果：

#一级标题
##二级标题
###三级标题
####四级标题
	
###2.加粗/斜体

* 加粗

	     **加粗**
	     
效果为

**加粗**
	
* 斜体

		*斜体*
		
效果为：

*斜体*

### 3.序号和列表

* 序号

		1.第一点
		2.第二点

输出为

1. 第一点
2. 第二点

* 列表

		* 列表1
		* 列表2
输出为
* 列表1
* 列表2

注：

在列表中「*」、「+」、「-」的作用是等同的

序号和列表的符号和文字中间需要空格

### 4.引用
引用功能的效果是我喜欢用Markdown的一个原因，在传统的排版软件中，引用功能很难寻找，也没有这么**优雅**。

	> 引用就是这么优雅
	
效果为

>引用就是这么优雅

更多语法规则请参见[Markdown 语法说明](http://wowubuntu.com/markdown/#precode)
## Markdown的软件选择

想使用Markdown语言，其实用任何一个文本软件都可以，（手写也可以LOL），但是要转换成特定的一些格式（如PDF和html），保证预览效果，则需要安装一些软件。

Mac下[MOU](http://25.io/mou/)和[Macdown](http://macdown.uranusjr.com/)都不错，目前使用的是Macdown。

Windowns下[阳志平](http://www.yangzhiping.com/tech/r-markdown-knitr.html)推荐了[markdownpad](http://markdownpad.com/)

当然，想尝鲜的同学还可以试试在线编辑 [简书](http://www.jianshu.com/)是一个写作平台，网页版就支持Markdown语法。




##参考资料

[维基百科](http://zh.wikipedia.org/zh/Markdown)

[轻量级标记语言对比](http://www.worldhello.net/gotgithub/appendix/markups.html)

[Markdown 语法说明](http://wowubuntu.com/markdown/#precode)

[Markdown写作浅谈] (http://www.yangzhiping.com/tech/r-markdown-knitr.html)