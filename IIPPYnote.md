#IIPPy课程笔记 

## environment

codeskuptor

### varialbes

* = 为变量命名
*
### type of numbers
int(): 3,5,6

float(): 2.3234 4.23

tips: 3.0 is a float in python
	a float ,the rusult would be float

### 计算规则
* int/int 整除取整数商（直接去掉小数点后的数）

### expressions

### function

def 定义
方式

	def fuction(x):
	fuc=x*2
	return fuc
	
	fuc1=fuction(3)
	print fuc1
return 返回结果

### opetions

* % 求余数

具有最高的优先级

在东西超越屏幕时可以调用，使得物体始终在屏幕以内

* str 转换为字符串

用+ 可以连接

### logic

= 赋值
== 两边等同，一样

### 代码风格

""" 
紧跟函数后面，解释函数作用 

有if 就要和else 配对，出现没有列举的条件时就不会报none

### event driven progranm

### globallocal varialbes

* global
在function外部定义

### simpleGUI

步骤

* global statement
* helper function
* class
* define event handles
* creat a frame
* register event handles
* start frame&timers 

### buttons

### 代码风格
* 4个空格缩进代码
* 顶级定义之间空两行, 方法定义之间空一行
* 在二元操作符两边都加上一个空格, 比如赋值(=), 比较(==, <, >, !=, <>, <=, >=, in, not in, is, is not), 布尔(and, or, not). 至于算术操作符两边的空格该如何使用, 需要你自己好好判断. 不过两侧务必要保持一致.

### 标点
* print 语句末尾有，则与下一行的print连接到一行


### list

* in

是否在

	# 8是否在数列里，结果为true/false
	8 in list
* index

所在位置 

	lst.index(3)
	# 数列中第4个数字是什么（从0数起）

* append

添加

	lst.apped(2)
	# 添加2到数列中去
* pop

显示去掉的数字

	lst.pop()
	# 显示移除的数字
移除某一个数字

	lst.pop(2)
	#移除第三个数字（从0开始）
	
