---
typ: Terrain-Keyword
tags:
  - terrain-keyword
---

# Dickicht


**Dickicht** ist ein [[Terrain-Keyword]], das dicht bewachsenes und schwer zugängliches Gelände wie Dornenbüsche oder Dschungelunterholz darstellt.

## Regel
Immer, wenn ein Tier eine Angriffs-Aktion deklariert, erleidet es **1 direkten Schaden**.

**Ausnahme:** Das Tier erleidet keinen Schaden, wenn es die Fähigkeit [[Tarnung]] besitzt oder sich im [[Lauernd]]-Zustand befindet.



---
## Arenen mit diesem Terrain

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Dickicht")
SORT sterne DESC