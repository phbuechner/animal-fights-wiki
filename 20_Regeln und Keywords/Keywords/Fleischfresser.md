---
typ: "Keyword"
tags:
  - keyword
---


# Fleischfresser

Ein Keyword für Tiere, die sich primär von Fleisch ernähren.

## Alle Fleischfresser im Überblick

```dataview
TABLE sterne as "Sterne", stärke as "Stärke", verteidigung as "Verteidigung"
FROM #tierkarte
WHERE contains(keywords, "Fleischfresser")
SORT sterne DESC