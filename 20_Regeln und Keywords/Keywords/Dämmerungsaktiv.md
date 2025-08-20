---
typ: Keyword
tags:
  - keyword
  - aktivitätszyklus
---

# Dämmerungsaktiv

**Dämmerungsaktiv** ist ein [[Aktivitätszyklen|Aktivitätszyklus]] für Tiere, die in der Morgen- oder Abenddämmerung am aktivsten sind.

## Regeln
- Arenen mit dem Keyword "Dämmerung" können die Fähigkeiten oder Werte von dämmerungsaktiven Tieren beeinflussen.

---
## Alle dämmerungsaktiven Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Dämmerungsaktiv")
SORT sterne DESC