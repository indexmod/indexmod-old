---
title:
layout: cover
exclude: true
---

## List of articles

<ul>

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
  {% unless page.exclude %}
  <li class="intro">
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
  </li>
  {% endunless %}
 {% endfor %}
</ul>
