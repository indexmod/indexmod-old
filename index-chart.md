---
title: The chart
permalink: index-chart
layout: tech
exclude: true
---

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<a href="{{page.url|absolute_url}}">{% include indexmod-indicator.html %}</a>
 {% endunless %}
 {% endfor %}
</wrap>
