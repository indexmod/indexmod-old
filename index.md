---
layout: cover
title: Index
---

<!--- Do not change the "index.md" --->

# Index

<ul>

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
   <li class="intro">
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
  </li>
  {% endfor %}
  
</ul>
