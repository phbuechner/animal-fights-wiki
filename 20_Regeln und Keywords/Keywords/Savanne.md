---
typ: "Keyword"
tags:
  - keyword
  - habitat
---

# Savanne

Die **Savanne** ist ein [[Habitat-System|Habitat]] im Spiel. Sie wird charakterisiert durch weite Grasländer und vereinzelte Baumgruppen.

---
## Arenen in diesem Habitat

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(habitat, "Savanne")
SORT sterne DESC
```
## Tiere, die in diesem Habitat leben

``` dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★"
FROM #tierkarte
WHERE contains(habitat, "Savanne")
SORT sterne DESC
