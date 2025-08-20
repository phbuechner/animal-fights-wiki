---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Offenes Gelände

Das **Offenes Gelände**-Keyword repräsentiert Gebiete...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Offenes Gelände")
SORT sterne DESC