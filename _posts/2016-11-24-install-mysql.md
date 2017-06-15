---
layout: post
title: "Mac中安装MySQL"
subtitle: "Mac中安装MySQL"
date: 2016-11-24
tags: mysql Mac
---
> MySQL版本：5.7.16  
MySQL安装方式：.dmg文件  
系统版本：OS X 10.12

### 1.进入MySQL官网，[点击链接](http://dev.mysql.com/downloads/mysql/)
### 2.下载MySQL社区版（免费）
选择自己的系统版本，这里我们选择Mac OS X，下载DMG文档进行安装，这里的MD5码可用于验证下载的文件的完整性。  
<div align="center">
  <img src="{{ site.baseurl }}assets/img/install-mysql-1.png" class="img-no-border-radius"/>
</div>
点击”No thanks, just start my download.”开始下载。
<div align="center">
  <img src="{{ site.baseurl }}assets/img/install-mysql-2.png" class="img-no-border-radius"/>
</div>
### 3.验证文件的完整性(可跳过本步骤)
打开Terminal终端，输入`cd Downloads/`进入下载文件夹。  
<div align="center">
  <img src="{{ site.baseurl }}assets/img/install-mysql-3.png" class="img-no-border-radius"/>
</div>
输入`md5 文件名`校验MD5码，再和官网上的MD5码进行比较，相同则表示文件和官网文件一致，如果不同的话请重新下载。
<div align="center">
  <img src="{{ site.baseurl }}assets/img/install-mysql-4.png" class="img-no-border-radius"/>
</div>
### 4.进行安装
在Finder中双击文件进行安装，安装过程和其它程序安装过程一致，这里不再赘述。
