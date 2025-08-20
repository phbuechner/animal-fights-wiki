---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Schlamm

Das **Schlamm**-Keyword repräsentiert Gebiete ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Schlamm")
SORT sterne DESC