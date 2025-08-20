---
typ: "Keyword"
tags:
  - keyword
---

# Allesfresser

Ein "Allesfresser" ist ein Keyword, das Tiere beschreibt, die sich primär von Pflanzen wie auch Fleisch ernähren.

---
## Alle Pflanzenfresser im Überblick

```dataview
TABLE
  sterne as "Sterne",
  stärke as "Stärke",
  verteidigung as "Verteidigung",
  gesundheit as "Gesundheit"
FROM #tierkarte
WHERE contains(keywords, "Allesfresser")
SORT sterne DESC