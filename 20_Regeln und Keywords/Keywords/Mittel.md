---
typ: "Keyword"
tags:
  - keyword
  - größenkategorie
---

# Mittel

**Gigantisch** ist die größte [[Größenkategorien|Größenkategorie]] im Spiel. Tiere dieser Größe sind extrem widerstandsfähig und stark, aber oft langsam.

> Eine vollständige Übersicht und der Vergleich aller Größen findet sich auf der Hauptseite: **[[Größenkategorien]]**.

---
## Alle mittelgroßen Tiere

```dataview
TABLE
  sterne as "★",
  stärke as "S",
  verteidigung as "V",
  gesundheit as "G"
FROM #tierkarte
WHERE contains(keywords, "Mittel")
SORT gesundheit DESC