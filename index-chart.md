---
title: The chart
permalink: index-chart
layout: cover
exclude: true
---

# The chart

<wrap>
{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<a href="{{page.url|absolute_url}}">{% include indexmod-indicator.html %}</a>
 {% endunless %}
 {% endfor %}
</wrap>
