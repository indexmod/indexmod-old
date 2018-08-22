---
shortname: B
birth: 1990
facebook: 300000
instagram: 300000
permalink: indicator-b
layout: indicator
---

|Shortname|{{page.shortname}}|
|Facebook|{{page.facebook}}|
|Instagram|{{page.instagram}}|
|F+I|{{ social }}|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|
|Words|{{page.content | number_of_words}}|
|Total|{{ indexmod | round: 0 }}|
