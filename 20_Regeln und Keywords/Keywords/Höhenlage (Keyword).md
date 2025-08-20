---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Höhenlage

Das **Höhenlage**-Keyword repräsentiert Gebiete ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Höhenlage")
SORT sterne DESC