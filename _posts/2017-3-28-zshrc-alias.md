---
layout: post
title: "zsh下配置命令的别名"
description: "zsh下配置命令的别名"
date: 2017-3-28
tags: [zsh ,Ubuntu]
comments: true
share: true
---
> Ubuntu版本：16.04 LTS

### `Ctrl + Alt + T`打开终端。
### 输入`sudo vim ~/.zshrc`并回车。
### 添加命令别名
例：`alias ssopen='sslocal -c ~/shadowsocks.json -d start'`

之后按ESC键，键入:wq并回车，将会保存文件。
### 再输入`source ~/.zshrc`并回车，这步会将配置文件生效。
### 之后输入`ssopen`并回车的效果等于输入`sslocal -c ~/shadowsocks.json -d start`并回车。
