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
<figure>
<a href="{{ page.permalink | absolute_url }}">{% include indexmod-indicator.html %}</a>
<figcaption>
<p class="age">{% include age.html %}</p>
<p class="formula">×</p>
<p class="social">{% include social.html %}</p>
<p class="formula">×</p>
<p class="words">{% include words.html %}</p>
<p class="shortname">{{page.shortname}} | {% include indexmod.html %}</p></figcaption>
</figure>
{% endunless %}
{% endfor %}
</wrap>
