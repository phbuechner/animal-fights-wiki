---
typ: "Keyword"
tags:
  - keyword
  - tiertyp
---

# Primat

**Primat** ist ein Klassifizierungs-[[Keywords|Keyword]] für alle Affen und Menschenaffen.

## Regeln
Es dient dazu, diese Tiere für thematische Karten-Effekte zu gruppieren. Fähigkeiten, die auf Primat-Tiere abzielen, können durch das [[Größenkategorien|Größe-Keyword]] weiter eingeschränkt werden (z.B. "gegen Primat-Tiere der Größe Klein").

---
## Alle Primaten

```dataview
TABLE
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Primat")
SORT sterne DESC