---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Unterholz

Das **Unterholz**-Keyword repräsentiert Gebiete ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Unterholz")
SORT sterne DESC