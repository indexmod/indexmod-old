---
title: The Indexmod universe
permalink: universe
layout: tech-universe
exclude: true
---

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<div class="tooltip"><a href="{{page.url|absolute_url}}">{% include indexmod-indicator.html %}</a><span class="tooltiptext">{{page.shortname}}</span></div>
 {% endunless %}
 {% endfor %}
</wrap>
