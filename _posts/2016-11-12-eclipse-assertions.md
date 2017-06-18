---
layout: post
title: "eclipse中启动Java断言语句"
subtitle: "eclipse中使用-ea启用断言语句"
date: 2016-11-12
tags: java eclipse
---
> 本文为转载加翻译。
> [原文链接](http://stackoverflow.com/questions/5509082/eclipse-enable-assertions)

在编写Java程序时，我们有的时候会使用Java的断言语句来调试代码，这篇文章就是教你如何在eclipse中启用断言语句。

1.在菜单中点击 `Run`，再点击 `Run Configurations`。

<div align="center">
  <img src="{{ site.baseurl }}assets/img/eclipse-assertions-1.png" class="img-no-border-radius"/>
</div>

2.在左边的面板中, 点击 `Java Application`，再点击 `Assertions`。

3.在右边的面板中, 选中 `Arguments`。

4.在 `VM arguments` 输入框中, 输入 `-ea` 来启用断言语句。

<div align="center">
  <img src="{{ site.baseurl }}assets/img/eclipse-assertions-2.png" class="img-no-border-radius"/>
</div>

5.点击 `Apply` 按钮然后点击 `Run` 按钮.

---

##### 将其设置为全局设置

1.点击菜单中的 `Window` (如果你使用的是Windows)，或者点击菜单中的 `Eclipse` (如果你使用Mac)。Linux的话应该很相似。

2.点击 `Preferences`。

3.选择 `Java`, 然后在左边面板中点击 `Installed JREs`。

4.选择你的 `JRE`, 然后咋右边点击 `Edit...` 按钮。

5.在 `Default VM arguments` 输入框中, 添加 `-ea`。
