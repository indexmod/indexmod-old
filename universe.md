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
<div class="tooltip" class="universe"><a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator-2.html %}</a><span class="tooltiptext" class="universe">{{page.shortname}} {% include indexmod.html %}</span></div>

{% endunless %}
{% endfor %}
</wrap>

----

 <p>[Read the post about this visual concept at Medium.com: "SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»" (3 min.) ](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)</p>	Read the post about this visual concept at Medium.com: ["SVG индикаторы статистики в «альтернативной вселенной» проекта «Индексмод блокчейнпедия»" (3 min.) ](https://medium.com/@andreideinichenko/svg-индикаторы-статистики-в-альтернативной-вселенной-проекта-индексмод-блокчейнпедия-325dc5cf3c1b)
