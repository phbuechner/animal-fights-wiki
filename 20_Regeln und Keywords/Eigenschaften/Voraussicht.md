---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Voraussicht

**Regel:** Du darfst einmal pro Runde die drei obersten Karten des allgemeinen Decks anschauen. Lege eine davon oben auf den Stapel. Lege die anderen beiden Karten unter das Deck.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
