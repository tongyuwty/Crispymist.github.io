--
title: "原创文章"
permalink: /originals/
layout: archive
author_profile: true
---

## 原创文章

以下是我的原创非虚构写作和深度分析文章。

{% assign originals = site.portfolio | where: "category", "original" | sort: date | reverse %}
{% for item in originals %}
- **{{ item.date | date: "%Y-%m-%d" }}** [{{ item.title }}]({{ item.url }})
{% endfor %}


