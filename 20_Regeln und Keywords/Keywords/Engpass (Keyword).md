---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Engpass (Keyword)

Das **Engpass**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Engpass")
SORT sterne DESC