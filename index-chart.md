---
title:
layout: cover
exclude: true
---

# The articles

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
