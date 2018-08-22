---
title:
permalink: index-chart
layout: cover
exclude: true
---

# The articles

<wrap>

{% assign mypages = site.pages | sort: "order" %} {% for page in mypages %}
{% unless page.exclude %}

<a href="{{page.url|absolute_url}}"> {{ page.shortname }} {% include indexmod-indicator.html %} {% include indexmod.html %}</a>
 {% endunless %}
 {% endfor %}

</wrap>
