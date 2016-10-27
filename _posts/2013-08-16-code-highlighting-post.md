---
layout: post
title: "代码高亮 Syntax highlighting"
description: "在Markdown中显示各种各样的高亮代码。"
date: 2013-08-16
tags: [sample post, code, highlighting]
comments: true
share: true
---


**语法突显**（英语：Syntax highlighting，又称**语法高亮**、**语法加亮**），是指根据术语（关键字）类别来显示不同的颜色与字体以增强可读性的一种编辑器特性。  
这种功能可改善人对编辑器中内容（通常为源代码）的可读性，进而降低出现误读或误写而出现错误的几率。[^1]


[^1]: <https://zh.wikipedia.org/wiki/%E8%AA%9E%E6%B3%95%E7%AA%81%E9%A1%AF>

### 代码高亮块

自定义样式和颜色可以编辑这个文件 `/_sass/_highlighter.scss`。

```css
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
```

```html
{% raw %}<nav class="pagination" role="navigation">
    {% if page.previous %}
        <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
    {% endif %}
    {% if page.next %}
        <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
    {% endif %}
</nav><!-- /.pagination -->{% endraw %}
```

```ruby
module Jekyll
  class TagIndex < Page
    def initialize(site, base, dir, tag)
      @site = site
      @base = base
      @dir = dir
      @name = 'index.html'
      self.process(@name)
      self.read_yaml(File.join(base, '_layouts'), 'tag_index.html')
      self.data['tag'] = tag
      tag_title_prefix = site.config['tag_title_prefix'] || 'Tagged: '
      tag_title_suffix = site.config['tag_title_suffix'] || '&#8211;'
      self.data['title'] = "#{tag_title_prefix}#{tag}"
      self.data['description'] = "An archive of posts tagged #{tag}."
    end
  end
end
```


### 普通代码块

    {% raw %}<nav class="pagination" role="navigation">
        {% if page.previous %}
            <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
        {% endif %}
        {% if page.next %}
            <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
        {% endif %}
    </nav><!-- /.pagination -->{% endraw %}

### 嵌入GitHub Gist

下面是一个嵌入Gist的例子。

<script src="https://gist.github.com/wjjwkwindy/57c47a7b8ab0749fd3e509ae3c7c6977.js"></script>
