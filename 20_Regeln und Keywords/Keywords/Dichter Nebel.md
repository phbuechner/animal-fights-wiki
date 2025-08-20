---
typ: "Terrain-Keyword"
tags:
  - terrain-keyword
---

# Dichter Nebel

**Dichter Nebel** ist ein [[Terrain-Keyword]], das die Sichtverhältnisse auf dem Schlachtfeld stark einschränkt.

## Regel
Alle Angriffswürfe (W6) in dieser Arena erhalten einen festen Malus von **-1**.

---
## Arenen mit diesem Terrain

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★", 
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Dichter Nebel")
SORT sterne DESC