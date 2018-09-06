---
title: The Indexmod Under-Universe
permalink: universe
layout: tech-universe
exclude: true
---
<wrap>

{% assign mypages = site.html_pages | sort: "order" %}
{% for page in mypages %}
{% unless page.exclude %}
<figure>
<a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator.html %}</a>
<figcaption>
<p class="age">{% include age.html %}</p>
<p class="formula">×</p>
<p class="social">{% include social.html %}</p>
<p class="formula">×</p>
<p class="words">{{page.content | number_of_words}}</p>
<p class="shortname">{{page.shortname}}</p></figcaption>
</figure>
{% endunless %}
{% endfor %}
</wrap>
