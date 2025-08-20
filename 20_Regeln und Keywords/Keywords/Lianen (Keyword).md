---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Lianen

Das **Lianen**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Lianen")
SORT sterne DESC