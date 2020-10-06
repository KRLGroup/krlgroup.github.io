---
title: "News"
layout: textlay
excerpt: "KRL Research Group"
sitemap: false
permalink: /allnews.html
---

<h1 class="sapienza-text"> News </h1>

{% for article in site.data.news %}
<p><b>{{ article.date }}<b> <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
