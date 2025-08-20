---
typ: "Keyword"
tags:
  - keyword
  - klimazone
---

# Tropisch

**Tropisch** beschreibt feuchte und warme [[Klimazonen]], wie sie in Regenwäldern und Sumpfgebieten zu finden sind.

## Regeln & Effekte
Tropische Klimazonen sind oft mit den [[Terrain-Keyword|Terrain-Keywords]] [[Wasser (Keyword)|Wasser]] und [[Schlamm (Keyword)|Schlamm]] sowie mit dem Effekt **[[Monsun]]** verbunden.

---
## Arenen in dieser Klimazone

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  habitat as "Habitat",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(klima, "Tropisch")
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
WHERE contains(klimazone, "Tropisch")
SORT sterne DESC