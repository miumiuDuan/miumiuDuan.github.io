---
layout: post
title: "How to post a blog"
date: 2016-8-8 21:32:59
---

# 如何发布一篇 Blog

需要在 Blog 中发布的文章，要写成后缀名为 .md 的 Markdown 格式的文件，并放在根目录下面的 posts 文件夹中。

<!--more-->

### 文件命名

文件的命名应为

    Year-month-date-topic-topic-topic.md

例如本文为

    2016-08-08-how-to-post-a-blog

### 开头格式

在 .md 文件中至少应包含如下的开头：

    ---
    layout: post
    title: "How to post a blog"
    date: 2016-8-8 21:32:59
    ---

上述声明中，指定 layout 方式为 post，并注明发布文章的 title 和 date。

### 文章摘要

看到上述文件中有

    <!--more-->

字样，在此内容之上的内容，均会在 page 页被显示为文章摘要。

### 文章写法

关于 Markdown 的基本写法，查阅[献给写作者的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)。

相关编辑器推荐使用 [Atom](https://atom.io/)，支持 git
文件标识和 Markdown 文件预览。

写好 Markdown 文件后，使用 git 将文章自动 push 到远端，片刻之后文章即会渲染完成。

