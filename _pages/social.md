---
title: "社交媒体"
permalink: /social/
layout: archive
author_profile: true
---

## 小红书运营记录

小红书账号：@【你的ID】
定位：文艺/幽默/双语日常分享

### 核心数据

| 指标 | 当前 | 目标 |
|------|------|------|
| 粉丝数 | 【待填写】 | 1000（3个月内） |
| 累计发布 | 【待填写】 | 90篇（3个月） |
| 平均点赞 | 【待填写】 | 100+ |

### 代表帖子

{% assign socials = site.portfolio | where: "category", "social-media" | sort: date | reverse %}
{% for item in socials %}
- **{{ item.date | date: "%Y-%m-%d" }}** [{{ item.title }}]({{ item.url }}) — *{{ item.platform }}*
{% endfor %}


