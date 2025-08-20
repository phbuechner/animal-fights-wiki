---
typ: "Keyword"
tags:
  - keyword
  - habitat
---

# Trockengebiet

Das **Trockengebiet** ist ein [[Habitat-System|Habitat]] das trockene, karge Landschaften wie Wüstenränder, Steppen und Trockensavannen umfasst.

---
## Arenen in diesem Habitat

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(habitat, "Trockengebiet")
SORT sterne DESC
```
### Tiere, die in diesem Habitat leben

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(habitat, "Trockengebiet")
SORT sterne DESC