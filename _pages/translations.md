---
title: "编译作品"
permalink: /translations/
layout: archive
author_profile: true
---

## 编译作品集

以下是我的双语编译作品。每篇都附有原文来源和编译笔记。

{% assign translations = site.portfolio | where: "category", "translation" | sort: date | reverse %}
{% for item in translations %}
- **{{ item.date | date: "%Y-%m-%d" }}** [{{ item.title }}]({{ item.url }}) — *来源：{{ item.source }}*
{% endfor %}


