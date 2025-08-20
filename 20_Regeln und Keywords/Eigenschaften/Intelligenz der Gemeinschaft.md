---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Intelligenz der Gemeinschaft

**Regel:** Am Ende deines Zuges, wenn du in diesem Zug eine Instinktkarte gespielt hast, darfst du dir die obersten 3 Karten deines Decks ansehen. Nimm eine Instinktkarte davon auf deine Hand und lege die anderen beiden unter dein Deck.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


