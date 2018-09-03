---
title: The Indexmod Under-Universe
shortname: Under-universe
permalink: universe
birth: 2018
layout: tech-universe
exclude: true
---
<wrap>
{% assign my pages = site.html_pages | sort: "order" %}
{% for page in my pages %}
{% unless page.exclude %}
<a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator.html %}</a>
{% end unless %}
{% end for %}
</wrap>
