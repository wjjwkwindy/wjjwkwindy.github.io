---
layout: post
title: "解决你需要来自TrustedInstaller的权限才能对此文件夹进行更改"
description: "Win10下删除或修改文件时提示你需要来自TrustedInstaller的权限才能对此文件夹进行更改"
date: 2016-10-30
tags: [windows]
comments: true
share: true
---

> 本文为转载加翻译。
> [原文链接](http://fixpcnyc.com/you-require-permission-from-trustedinstaller-to-make-changes-to-this-folder-fixed/)

因为笔记本固态硬盘装满了，今天在光驱位上加上了之前换下来的机械硬盘，但是在删除机械硬盘上残留的windows文件时提示“你需要来自TrustedInstaller的权限才能对此文件夹进行更改”。

<div align="center">
  <img src="http://i.imgur.com/MvEN50q.png" class="img-no-border-radius"/>
</div>

提示需要TrustedInstaller权限一般包含重要的windows文件，所以当你删除它时需要保持小心。

解决办法可用于Windows 10, Windows 8.1 和 Windows 7。

## 如何从TrustedInstaller获取权限来删除文件夹

你可以通过成为文件夹的拥有者来轻松的删除它并且获得相应的权限。以下是你需要做的步骤：

1.右键点击文件夹然后选择“属性”选项。然后打开“安全”选项。

<div align="center">
  <img src="http://imgur.com/AheQE5W.png" class="img-no-border-radius"/>
</div>

2.点击“高级”按钮。

3.在“所有者”栏，点击“更改”来从TrustedInstaller改变文件夹所有者。

<div align="center">
  <img src="http://imgur.com/HHkvYcD.png" class="img-no-border-radius"/>
</div>

4.在“选择用户或组”窗口中点击“高级”按钮。

<div align="center">
  <img src="http://imgur.com/ZVldi7a.png" class="img-no-border-radius"/>
</div>

5.点击“立即查找”并在列表中选择你的用户名。点击“确认”，再点击“确认”。

<div align="center">
  <img src="http://imgur.com/WCRTwaC.png" class="img-no-border-radius"/>
</div>

6.选中“替换子容器和对象的所有者”，再点击“确认”。(注：文件夹包含文件较多时，需要等待一段时间)

<div align="center">
  <img src="http://imgur.com/hXege5W.png" class="img-no-border-radius"/>
</div>

7.再一次点击“安全”选项窗口中的“高级”按钮。

8.点击“更改权限”按钮，再点击“添加”按钮。（注：如果没有看到“更改权限”，就直接点击“添加”）

9.点击“选择主体”，然后和第5步中一样选择你的用户名。

10.在基本权限中选中“完全控制”，再点击“确认”。

<div align="center">
  <img src="http://imgur.com/rRtIfMh.png" class="img-no-border-radius"/>
</div>

11.选中“使用可从此对象继承的权限项目替换所有子对象的权限项目”。

<div align="center">
  <img src="http://imgur.com/XGDUnPD.png" class="img-no-border-radius"/>
</div>

12.点击“确认”按钮。(注：文件夹包含文件较多时，需要等待一段时间)

一旦你完成了以上步骤，你就被允许删除文件夹，你就不会看到任何说你需要从TrustedInstaller获取权限的窗口。
