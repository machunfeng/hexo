---
title: Markdown学习笔记
date: 2018-10-07 21:46:52
tags: Markdown
---
# **Markdown是什么**
>与Word类似用来编写文档,只是Word编写完后还需要格式化文档如添加粗体组织结构等,而Markdown使用纯文本格式编写文档,也就是说编写和格式化文档一气呵成,无需再次组织.好处是简单方便,坏处是新手需要记住一些语法,一开始不习惯很容易放弃.

# 在线 Markdown **编辑器**
一边学习Markdown语法一边[在线练习 Markdown 编辑器](https://www.zybuluo.com/mdeditor)

# **Markdown语法**(通用)
## **标题**
用 **#**

>\# 一级标题<br>
\# 二级标题<br>
\## 三级标题<br>
\### 四级标题<br>
\#### 五级标题<br>
\##### 六级标题<br>

结果

># 一级标题
>## 二级标题
>### 三级标题
>#### 四级标题
>##### 五级标题
>###### 六级标题

## **换行**
>在文本中输入的换行会从最终生成的结果中删除，浏览器会根据可用空间自动换行。如果想强迫换行，可以在行尾插入至少两个空格,或者使用断行标签\<br/>.

## **引用**

用 **>**

>\> 区块引用  
\>> 嵌套引用

结果
> 区块引用
>> 嵌套引用

## **强调**
用*或者_

>\*斜体*，\_斜体_  
\**粗体**，\_粗体_

结果

>*斜体*，_斜体_  
>**粗体**，__粗体__

## **列表**
用·、+、-、数字加.

>-（+*） 第一项 -（+*） 第二项 - （+*）第三项

>1 . 第一项
2 . 第二项
3 . 第三项

结果

>- 第一项 
>- 第二项 
>- 第三项

>1. 第一项
>2. 第二项
>3. 第三项

## **链接**
用\[链接文字](链接地址)

>\[Markdown](http://zh.wikipedia.com/wiki/Markdown)

结果

>[Markdown](http://zh.wikipedia.com/wiki/Markdown)

## **图片**
用\!\[Foo](url)

## **分割线**
用三个或以上*，-或_。

>\*****

结果

>*****

## **反斜杠\\**
用在符号前面,使符号成为普通符号。

