---
title: The Indexmod universe
permalink: universe
layout: tech-universe
exclude: true
---

<wrap>
{% assign mypages = site.posts | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<div class="tooltip"><a href="{{page.url|absolute_url}}">{% include indexmod-indicator.html %}</a><span class="tooltiptext">{{page.shortname}}</span></div>
 {% endunless %}
 {% endfor %}
</wrap>

[Read about visual concept of The Indexmod universe in the article of "SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»" (at Medium)](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)
