---
title: 安装
layout: default
localization: zh-CN
---

# 有关安装的主题

<ul>
{% for article in site.data.install.articles %}

{% include article/link.html article=article[1] %}

{% endfor %}
</ul>