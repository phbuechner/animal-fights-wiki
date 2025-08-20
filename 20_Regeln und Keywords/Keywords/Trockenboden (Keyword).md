---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Trockenboden

Das **Trockenboden**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Trockenboden")
SORT sterne DESC