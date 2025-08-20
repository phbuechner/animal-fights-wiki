---
typ: "Keyword"
tags:
  - keyword
  - habitat
---

# Wald

Der **Wald** ist ein [[Habitat-System|Habitat]], das durch dichten Baumbestand geprägt ist und oft die [[Terrain-Keyword|Terrain-Keywords]] [[Unterholz (Keyword)|Unterholz]] und [[Baumkronen (Keyword)]] aufweist.

## Arenen in diesem Habitat

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(habitat, "Wald")
SORT sterne DESC
```
## Tiere, die in diesem Habitat leben

``` dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★"
FROM #tierkarte
WHERE contains(habitat, "Wald")
SORT sterne DESC

