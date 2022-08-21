---
title: 评论功能
date: 2022-08-14T21:34:36+08:00
tags: ["hugo", "ladder", "Tutorial", "comment"]
series: ["how to create your blog"]
featured: true
---
本文关于如何集成评论功能，在文章末尾或者留言板中显示评论信息。
<!--more-->
### Comment Systems

在文章末尾或者留言板中显示评论信息。

#### Giscus

Follow [these steps](https://giscus.app/).

```yml
params:
  comments:
    giscus:
      enable: true
      repo: username/reponame
      repo_id: Rid
      category: Announcements
      category_id: DIC_id
      mapping: pathname
      position: top
      lang: en # pick a language from https://github.com/giscus/giscus/tree/main/locales
```

#### Utterances

Follow [these steps](https://utteranc.es/)

```yml
params:
  comments:
    utteranc:
      enable: false
      repo: username/reponame
      issueTerm: pathname
```