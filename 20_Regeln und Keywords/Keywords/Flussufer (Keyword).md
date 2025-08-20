---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Flussufer

Das **Flussufer**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Flussufer")
SORT sterne DESC