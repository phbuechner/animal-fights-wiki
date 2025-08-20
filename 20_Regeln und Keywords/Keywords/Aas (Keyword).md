---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Aas

Das **Aas**-Keyword repräsentiert Gebiete mit Kadavern und Überresten, wie z.B. einen Knochenfriedhof. Es interagiert oft mit Tieren, die die Fähigkeit [[Aasfresser]] besitzen.

---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Aas")
SORT sterne DESC