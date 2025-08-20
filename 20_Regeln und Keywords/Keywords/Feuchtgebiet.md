---
typ: "Keyword"
tags:
  - keyword
  - habitat
---

# Feuchtgebiet

Das **Feuchtgebiet** ist ein [[Habitat-System|Habitat]], das durch die ständige Präsenz von Wasser geprägt ist, wie z.B. Sümpfe, Flussdeltas und überschwemmte Ebenen.

---
## Arenen in diesem Habitat

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(habitat, "Feuchtgebiet")
SORT sterne DESC
```
## Tiere, die in diesem Habitat leben
```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(habitat, "Feuchtgebiet")
SORT sterne DESC