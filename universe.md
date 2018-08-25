---
title: The Indexmod universe
shortname: This universe
permalink: universe
layout: tech-universe
facebook: 100
birth: 0001
exclude: true
---

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<div class="tooltip"><a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator.html %}</a><span class="tooltiptext">{{page.shortname}}</span></div>
 {% endunless %}
 {% endfor %}
</wrap>

[(3 min reading time) Read the post about this visual concept at Medium.com: "SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»"](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)
