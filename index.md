---
title:
layout: cover
---

**List of articles**

<ul>

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
   <li class="intro">
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
  </li>
  {% endfor %}

</ul>
