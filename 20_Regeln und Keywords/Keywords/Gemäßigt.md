---
typ: "Keyword"
tags:
  - keyword
  - klimazone
---


# Gemäßigt

**Gemäßigt** beschreibt ausgeglichene [[Klimazonen]] ohne extreme Wetterbedingungen.


## Regeln & Effekte
In gemäßigten Klimazonen gelten in der Regel keine besonderen globalen Regeln, die das Klima betreffen.

---
## Arenen in dieser Klimazone

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  habitat as "Habitat",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(klima, "Gemäßigt")
SORT sterne DESC
```

## Tiere, die in dieser Klimazone leben

```dataview
TABLE WITHOUT ID
  file.link as "Tiere",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(klimazone, "Gemäßigt")
SORT sterne DESC