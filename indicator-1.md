---
shortname: A
birth: 2007
facebook: 500000
instagram: 600000
permalink: indicator-a
layout: indicator
---

|Shortname|{{page.shortname}}|
|Facebook|{{page.facebook}}|
|Instagram|{{page.instagram}}|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|
|Words|{{page.content | number_of_words}}|
|Total|{{ indexmod | round: 0 }}|
