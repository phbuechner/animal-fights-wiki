---
typ: "Terrain-Keyword"
tags:
  - terrain-keyword
---

# Deckung

**Deckung** ist ein [[Terrain-Keyword]], das anzeigt, dass das Schlachtfeld viele Versteckmöglichkeiten wie Felsen, hohe Gräser oder Baumstämme bietet.

## Regel
Jedes Mal, wenn ein Tier in einer Arena mit diesem Keyword verteidigt, darf sein Besitzer den **Würfelwurf des Angreifers einmal wiederholen lassen**. Der Angreifer ist gezwungen, das zweite Ergebnis zu verwenden.

---
## Arenen mit diesem Terrain

```dataview
TABLE WITHOUT ID
  file.link as "Arena", 
  sterne as "★", 
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Deckung")
SORT sterne DESC