---
shortname: 2
birth: 1980
facebook: 500
instagram: 500
permalink: indicator-2
layout: indicator
---

# Formula

|Variables|Value|Math|||
|Facebook|{{page.facebook}}|+|||
|Instagram|{{page.instagram}}|=|{{social}}|/|
|Population|1000000|=|1|x|
|Age|{{ site.time | date: "%Y" | minus: page.birth }}|=|10||
|Words|{{page.content | number_of_words}}|=|300|/|
||100|=|3||
|Total|Value|Math||{{ indexmod | round: 0 }}|
