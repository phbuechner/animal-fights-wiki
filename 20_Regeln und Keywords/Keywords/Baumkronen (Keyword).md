---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Baumkronen

Das **Baumkronen**-Keyword repräsentiert Gebiete mit hohen Bäumen, wie z.B. einen Marula-Bäumen. [[Kletternd]]e Tiere haben hier oftmals Vorteile.


---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Baumkronen")
SORT sterne DESC