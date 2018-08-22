---
shortname: A
birth: 1950
facebook: 300000
instagram: 300000
permalink: indicator-a
layout: indicator
---

|Shortname|{{page.shortname}}|
|Facebook|{{page.facebook}}|
|Instagram|{{page.instagram}}|
|F+I|{% include social.html %}|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|
|Words|{{page.content | number_of_words}}|
|Total|{% include indexmod.html %}|
