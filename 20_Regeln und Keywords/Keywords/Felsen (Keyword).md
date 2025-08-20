---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Felsen (Keyword)

Das **Felsen**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Felsen")
SORT sterne DESC