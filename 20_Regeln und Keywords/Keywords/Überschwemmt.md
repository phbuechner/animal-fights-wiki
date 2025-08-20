---
typ: "Terrain-Keyword"
tags:
  - terrain-keyword
---

# Überschwemmt

**Überschwemmt** ist ein [[Terrain-Keyword]], das anzeigt, dass das Schlachtfeld unter Wasser steht.

## Regel
Am Ende der Runde müssen alle [[Boden]]tiere ohne die Eigenschaft [[Amphibisch]] **1 Ausdauer** zahlen oder sie erleiden **1 direkten Schaden**.

---
## Arenen mit diesem Terrain

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★", 
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Überschwemmt")
SORT sterne DESC