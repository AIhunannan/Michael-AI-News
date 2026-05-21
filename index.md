---
layout: default
title: Michael AI News
---

# Michael AI News

面向 AI 硬件、端侧 AI、陪伴机器人、AI 玩具与 AI 消费电子的每日情报雷达。

这里沉淀每天自动筛选后的重要信号，重点关注技术变化如何进入真实产品、真实供应链和真实用户场景。

## 最新速递

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) · {{ post.date | date: "%Y-%m-%d" }}{% if post.lang %} · {{ post.lang }}{% endif %}
{% endfor %}
