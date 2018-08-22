---
shortname: B
birth: 2017
facebook: 4567888
instagram: 46583566237
permalink: indicator-b
layout: indicator
---

|Shortname|{{page.shortname}}|
|Facebook|{{page.facebook}}|
|Instagram|{{page.instagram}}|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|
|Words|{{page.content | number_of_words}}|
|Total|{{ indexmod | round: 0 }}|
