---
shortname: INDIKATOR
birth: 2008
facebook: 600000
instagram: 400000
permalink: indicator
layout: indicator
---

# Formula

|Variables|Value|Math|||
|Facebook|{{page.facebook}}|+|||
|Instagram|{{page.instagram}}|=|1000000|/|
|Population|1000000|=|1|x|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|=|{{ index | round: 0 }}||
|Words|{{page.content | number_of_words}}|=|170|/|
||100|=|1.7||
|Total|Value|Math||{{ indexmod | round: 0 }}|
