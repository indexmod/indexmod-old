---
title: The Indexmod universe
shortname: This universe
permalink: universe
layout: tech-universe
facebook: 0
birth: '2018'
exclude: true
---

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<div class="tooltip"><a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator-2.html %}</a><span class="tooltiptext">{% include indexmod.html %} | {{page.shortname}}</span></div>
 {% endunless %}
 {% endfor %}
</wrap>

<hr>

<p>[Read the post about this visual concept at Medium.com: "SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»" (3 min.) ](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)</p>
