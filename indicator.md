---
shortname: INDIKATOR
birth: 1984
facebook: 150000
instagram: 2000000
permalink: indicator
layout: indicator
---

# Formula

|Variables|Value|Math|||
|Facebook|{{page.facebook}}|+|||
|Instagram|{{page.instagram}}|=|1000000|/|
|Population|1000000|=|1|x|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|=|10||
|Words|{{page.content | number_of_words}}|=|300|/|
||100|=|3||
|Total|Value|Math||{{ indexmod | round: 0 }}|
