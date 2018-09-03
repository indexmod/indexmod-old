---
title: The Indexmod Under-Universe
shortname: Under-universe
permalink: universe
birth: 2018
layout: tech-universe
exclude: true
---
<wrap>
{% assign mypages = site.html_pages | sort: "order" %}
{% for page in mypages %}
{% unless page.exclude %}
<a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator.html %}</a>
{% endunless %}
{% endfor %}
</wrap>
