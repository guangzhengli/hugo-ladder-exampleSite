---
title: Analytics
date: 2022-08-14T21:34:36+08:00
tags: ["hugo", "ladder", "Tutorial", "analytics"]
series: ["how to create your blog"]
featured: true
---
This article is about how to integrate website statistics analysis.
<!--more-->
## Analytics

## Google Analytics

Follow [these steps](https://gohugo.io/templates/internal/#configure-google-analytics).

### Google Tag Manager

Follow [these steps](https://developers.google.com/tag-manager).

```yml
params:
	analytics:
		google:
			SiteVerificationTag: gid
```

### Umami Analytics

Follow [these steps](https://guangzhengli.com/blog/en/how-to-integrate-umami-for-free-to-blog-site/).

```yml
params:
	analytics:
		umami:
      enable: true
      website_id: data-website-id
      url: https://umami-ochre-nu.vercel.app/hugo-ladder.js
```

