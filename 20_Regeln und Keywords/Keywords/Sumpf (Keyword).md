---
typ: Terrain-Keyword
tags:
  - terrain-keyword
  - wasser-terrain
---

# Sumpf

Das **Sumpf**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Sumpf")
SORT sterne DESC