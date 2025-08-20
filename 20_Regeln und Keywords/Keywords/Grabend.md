---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
---

# Grabend

**Grabend** ist ein [[Bewegungstypen|Bewegungstyp]] für Tiere, die sich durch die Erde bewegen oder unterirdische Baue anlegen.

## Regeln
- Interagiert oft mit Arenen, die das [[Terrain-Keyword]] [[Höhle (Keyword)|Höhle]] oder [[Unterholz (Keyword)|Unterholz]] haben.
- Kann bestimmte Effekte ignorieren, die nur Bodenziele betreffen.

---
## Alle grabenden Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  verteidigung as "V"
FROM #tierkarte
WHERE contains(keywords, "Grabend")
SORT verteidigung DESC