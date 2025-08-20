---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
---

# Kletternd

**Kletternd** ist ein spezieller [[Bewegungstypen|Bewegungstyp]], der es Tieren erlaubt, Hindernisse zu überwinden.

## Regeln
- **Ignoriert den Malus** gegen [[Fliegend]]e Ziele.
- Kann von [[Felsenspringer]]-Fähigkeiten nicht ignoriert werden.
- Interagiert oft mit Arenen, die das [[Terrain-Keyword]] [[Felsen (Keyword)|Felsen]] oder [[Baumkronen (Keyword)|Baumkronen]] haben.

---
## Alle kletternden Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Kletternd")
SORT agilität DESC