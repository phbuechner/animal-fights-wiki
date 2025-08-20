---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Höhle

Das **Höhle**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Höhle")
SORT sterne DESC