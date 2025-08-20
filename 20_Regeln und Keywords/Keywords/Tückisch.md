---
typ: "Terrain-Keyword"
tags:
  - terrain-keyword
---

# Tückisch

**Tückisch** ist ein [[Terrain-Keyword]], das unvorhersehbares und gefährliches Gelände wie Sümpfe oder instabile Felsen beschreibt.

## Regel
Immer, wenn ein Tier eine Aktion ausführt, muss sein Besitzer einen W6 würfeln. Bei einer **1 wird die Aktion annulliert**. Die Kosten (AP, Ausdauer) sind trotzdem verbraucht.

---
## Arenen mit diesem Terrain

```dataview
TABLE
  file.link as "Arena", 
  sterne as "★", 
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Tückisch")
SORT sterne DESC