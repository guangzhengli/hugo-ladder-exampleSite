---
title: 网站数据统计分析
date: 2022-08-14T21:34:36+08:00
tags: ["hugo", "ladder", "Tutorial", "analytics"]
series: ["how to create your blog"]
featured: true
---
本文关于如何集成网站数据统计分析。
<!--more-->
## Analytics

## Google Analytics

详情点击 [these steps](https://gohugo.io/templates/internal/#configure-google-analytics).

### Google Tag Manager

详情点击 [these steps](https://developers.google.com/tag-manager).

```yml
params:
	analytics:
		google:
			SiteVerificationTag: gid
```

### Umami Analytics

详情点击 [these steps](https://guangzhengli.com/blog/en/how-to-integrate-umami-for-free-to-blog-site/).

```yml
params:
	analytics:
		umami:
      enable: true
      website_id: data-website-id
      url: https://umami-ochre-nu.vercel.app/hugo-ladder.js
```

