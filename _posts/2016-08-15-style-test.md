---
layout: post
title: "综合样式测试"
description: "测试文章的样式"
date: 2016-08-15
tags: [test, style]
comments: true
share: true
---

下面是所有你需要在主题中应用的样式。通过源代码来查看在段落中插入的许多元素。
# 正文

---

# 标题 1

## 标题 2

### 标题 3

#### 标题 4

##### 标题 5

###### 标题 6

Lorem ipsum dolor sit amet, [test link](#) adipiscing elit. **This is strong.** Nullam dignissim convallis est. Quisque aliquam. *This is emphasized.* Donec faucibus. Nunc iaculis suscipit dui. 5<sup>3</sup> = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget `COPY filename` sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, <del>Dinner’s at 5:00.</del> commodo vitae, feugiat in, nunc. Morbi imperdiet augue <mark>mark element</mark> quis tellus.

# 图片

![Large example image](http://placehold.it/800x400 "Large example image")
![Medium example image](http://placehold.it/400x200 "Medium example image")
![Small example image](http://placehold.it/200x200 "Small example image")

# 引用

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

# 列表类型

### 有序列表

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### 无序列表

* Item one
  * sub item one
  * sub item two
  * sub item three
* Item two
* Item three

### 自定义列表

kramdown
: A Markdown-superset converter

Maruku
: Another Markdown-superset converter

# 表格

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3


# 代码段

代码高亮 via Rouge

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

没有运用Pygments的代码示例

    <div id="awesome">
        <p>This is great isn't it?</p>
    </div>
