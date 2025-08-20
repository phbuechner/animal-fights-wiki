---
typ: "Keyword"
tags:
  - keyword
  - klimazone
---

# Arid

**Arid** beschreibt trockene, heiße und wasserarme [[Klimazonen]], wie sie in Wüsten, Steppen und Trockensavannen vorherrschen.

## Regeln & Effekte
Aride Klimazonen sind oft mit dem Effekt **[[Extreme Hitze]]** verbunden, der die Regeneration von [[Ausdauer]] für alle Tiere reduziert. Tiere, die an aride Zonen angepasst sind, können diesen Malus oft ignorieren oder davon profitieren.

---
## Arenen in dieser Klimazone

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  habitat as "Habitat",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(klima, "Arid")
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
WHERE contains(klimazone, "Arid")
SORT sterne DESC