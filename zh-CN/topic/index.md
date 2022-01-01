---
title: 主题
layout: default
localization: zh-CN
---

# 主题

{% include article/topic-list.html 
  topics=site.data.topic
%}

<ul class="article-list-page-ul">
    {% for topic in site.data.topic %}

    {% assign topicKey=topic[0] %}
    {% assign topicValue=topic[1] %}

    {% include article/topic-link.html topic=topicValue %}

    {% endfor %}
</ul>
