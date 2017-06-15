---
layout: post
title: "zsh下配置命令的别名"
subtitle: "zsh下配置命令的别名"
date: 2017-03-28
tags: zsh Ubuntu
---
> Ubuntu版本：16.04 LTS

### 1.打开终端
使用`Ctrl + Alt + T`打开终端。
### 2.打开zsh配置文件
输入`sudo vim ~/.zshrc`并回车。
### 2.添加命令别名
例：`alias ssopen='sslocal -c ~/shadowsocks.json -d start'`

之后按ESC键，键入:wq并回车，将会保存文件。
### 3.使配置文件生效
输入`source ~/.zshrc`并回车，这步会将配置文件生效。
### 4.使用命令的别名
输入`ssopen`命令的效果等于输入`sslocal -c ~/shadowsocks.json -d start`。
