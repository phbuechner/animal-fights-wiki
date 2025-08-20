---
typ: "Keyword"
tags:
  - keyword
  - aktivitätszyklus
---

# Nachtaktiv

**Nachtaktiv** ist ein [[Aktivitätszyklen|Aktivitätszyklus]] für Tiere, die hauptsächlich während der Nacht jagen und aktiv sind.

## Strategischer Vorteil bei Nacht
Nachtaktive Tiere sind die einzigen, die von der globalen Regel des [[Nacht (Keyword)|Kampfes bei Nacht]] **nicht** negativ betroffen sind. Sie kämpfen unter diesen Bedingungen ohne Einschränkungen, was ihnen einen erheblichen Vorteil gegenüber nicht-nachtaktiven Tieren verschafft.

Arenen mit dem Keyword [[Nacht (Keyword)|Nacht]] können die Fähigkeiten oder Werte von nachtaktiven Tieren zusätzlich positiv beeinflussen.

---
## Alle nachtaktiven Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Nachtaktiv")
SORT agilität DESC