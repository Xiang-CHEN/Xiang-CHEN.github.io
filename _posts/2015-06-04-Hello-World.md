---
layout: post
title: Hello Github.IO, Jekyll, Bootstrap, and Markdown
date: 2015-06-04
categories: 下拉电阻
tag: 前端
---

本博客挂载在 GitHub Pages 上，博客由 [Jekyll](http://jekyllrb.com/) 搭建，采用 [Bootstrap](http://getbootstrap.com/) 前端框架。博文由 Markdown 撰写，使用 [kramdown](http://kramdown.gettalong.org/) 解析，使用 [Markdown Here](http://markdown-here.com/) 的 CSS 文件渲染。博文的自动目录生成采用 [ghiculescu](https://github.com/ghiculescu/jekyll-table-of-contents) 的开源项目，scrollspy 功能由 [Bootstrap](http://getbootstrap.com/) 提供，代码高亮使用 [highlight.js](https://highlightjs.org/)。

作为 Hello World，本页面用于测试。测试代码基于 [Markdown Here](http://markdown-here.com/) 提供的测试内容修改。

```javascript
function syntaxHighlighting() {
  var n = 33;
  var s = "hello, こんにちは";
  console.log(s);
}
```

* plain
* *emphasis*
  * **strong emphasis**
    * ~~strikethrough~~
* `inline code`

1. Numbered list
   1. Numbered sub-list
      1. Numbered sub-sub-list
2. [Link](https://www.google.com)


An image: ![Markdown Here logo](http://adam-p.github.io/markdown-here/img/icon24.png) 

> Block quote.
> *With* **some** `markdown`.

**MathJax** is used by kramdown to support inline equation $ax_1+bx_2=0$ and display equation

$$-b \pm \sqrt{b^2 - 4ac} \over 2a$$

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6
  
| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| column 3 is | right-aligned | $1600 |
| column 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

Here's a horizontal rule:

---

```
code block
with no highlighting
```
