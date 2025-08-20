---
typ: "Keyword"
tags:
  - keyword
  - aktivitätszyklus
---

# Tagaktiv

**Tagaktiv** ist ein [[Aktivitätszyklen|Aktivitätszyklus]] für Tiere, die hauptsächlich während des Tages aktiv sind.

## Regeln
- Wenn nicht anders angegeben, finden die Arenen immer am Tag statt.

---
## Alle tagaktiven Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Tagaktiv")
SORT sterne DESC