---
title: The Indexmod universe
shortname: This universe
permalink: universe
layout: tech-universe
exclude: true
---

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}
<a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator-2.html %}</a>
{% endunless %}
{% endfor %}
</wrap>

<hr>

Read the post about this visual concept at Medium.com: ["SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»" (3 min.)](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)
