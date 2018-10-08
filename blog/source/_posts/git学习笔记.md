---
title: git学习笔记
date: 2018-10-07 23:29:29
tags: git
---
## **git是什么**
>git是一个分布式版本控制系统,简单说就是追踪恢复到每一个文件代码的修改点,使你不容易丢失你的数据信息,它最强大的地方就是它的合并追踪能力.由于概念太多了,这里主要介绍我学习git的一些有用的资料.  
## **教程资料**
>[Pro Git](https://git-scm.com/book/zh/v2)  
[廖雪峰的Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## **git命令**

### **配置**

>$ git config --global user.name "your name"  
$ git config --global user.email your-email@example.com

### **初始化仓库**
>$ git init

### **克隆仓库**
>git clone [url] 

### **跟踪新文件**
>git add [files]

### **提交更新**
> git commit

### **移除文件**
>git rm

### **查看远程仓库**
>git remote

### **添加远程仓库**
>git remote add \<shortname> \<url>

### **从远程仓库中抓取与拉取**
>git fetch [remote-name]

### **推送到远程仓库**
>git push [remote-name] [branch name]

### **分支创建**
>git branch [name]

### **分支切换**
>git checkout [name]

### **分支的合并**
>git merge [name]
