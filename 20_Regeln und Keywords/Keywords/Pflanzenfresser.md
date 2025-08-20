---
typ: "Keyword"
tags:
  - keyword
---

# Pflanzenfresser

Ein "Pflanzenfresser" ist ein Keyword, das Tiere beschreibt, die sich primär von Pflanzen ernähren.

---
## Alle Pflanzenfresser im Überblick

```dataview
TABLE
  sterne as "Sterne",
  stärke as "Stärke",
  verteidigung as "Verteidigung",
  gesundheit as "Gesundheit"
FROM #tierkarte
WHERE contains(keywords, "Pflanzenfresser")
SORT sterne DESC