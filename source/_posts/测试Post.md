---
title: GitHub+Hexo 搭建个人网站
date: 2019-09-21 14:07:51
categories: 
           - Hexo
tags:
           - 博客
---
使用npm命令安装Hexo，输入：
```bash
npm install -g hexo-cli 
```
这个安装时间较长耐心等待，安装完成后，初始化我们的博客，输入： 
```bash
hexo init blog
```
注意，这里的命令都是作用在刚刚创建的Blog文件夹中。

为了检测我们的网站雏形，分别按顺序输入以下三条命令：
```bash
hexo new test_my_site

hexo g

hexo s
```
这些命令在后面作介绍，完成后，打开浏览器输入地址：
```bash
localhost:4000
```
可以看出我们写出第一篇博客。