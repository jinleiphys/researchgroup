---
title: "News"
layout: textlay
excerpt: "同济大学任中洲教授课题组"
sitemap: false
permalink: /allnews.html
---

# 最新动态

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
