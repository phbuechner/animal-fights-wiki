---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Wasser

Das **Wasser**-Keyword repräsentiert Gebiete mit unspezifischen Wasserquellen, wie z.B. Tümpeln, Bächen oder Flüssen. 

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Wasser")
SORT sterne DESC