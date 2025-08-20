---
typ: "Keyword"
tags:
  - terrain-keyword
---

# Mangroven

Das **Mangroven**-Keyword repräsentiert Gebiete mit ...

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Mangroven")
SORT sterne DESC