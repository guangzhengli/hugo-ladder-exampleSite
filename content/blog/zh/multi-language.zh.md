---
title: 多语言支持
date: 2022-08-14T21:34:36+08:00
tags: ["hugo", "ladder", "Tutorial"]
series: ["how to create your blog"]
featured: true
---
本文是关于多语言支持。
<!--more-->
- [Available Languages](#available-languages)
- [Configure languages](#configure-languages)
- [Translation File Example](#translation-file-example)

## Available Languages

目前主题支持这些语言:

- 英语
- 简体中文

## Configure languages

跟随 [this Hugo documentation page](https://gohugo.io/content-management/multilingual/#configure-languages) 给你的网站配置语言。

## Translation File Example

```toml
[blog]
one = "blog"
other = "blog"

[tags]
one = "tag"
other = "tags"

[archive]
one = "archive"
other = "archive"

[series]
one = "series"
other = "series"

[reading_time]
one = "One minute"
other = "{{ .Count }} min"

[word_count]
one = "one word"
other = "{{ .Count }} words"

[related_resources]
other = "Related Resources"

[featured_posts]
one = "Featured Posts"
other = "Featured Posts"
```



```toml
[blog]
one = "文章"
other = "文章"

[tags]
one = "分类"
other = "分类"

[archive]
one = "历史文章"
other = "历史文章"

[series]
one = "系列文章"
other = "系列文章"

[reading_time]
one = "1 分钟"
other = "{{ .Count }} 分钟"

[word_count]
one = "字"
other = "{{ .Count }} 字"

[related_resources]
one = "相关系列文章推荐"
other = "相关系列文章推荐"

[featured_posts]
one = "推荐阅读"
other = "推荐阅读"
```

