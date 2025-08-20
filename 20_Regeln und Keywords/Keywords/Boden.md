---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
---

# Boden

**Boden** ist der Standard-[[Bewegungstypen|Bewegungstyp]]. Tiere mit diesem Keyword sind sogenannte "Bodentiere".

## Regeln
- Bodentiere erhalten einen Malus von **-2 auf ihr Angriffs-Ergebnis**, wenn sie ein Ziel mit dem Keyword [[Fliegend]] angreifen (es sei denn, sie haben selbst [[Fliegend]] oder [[Kletternd]]).

---
## Alle Bodentiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Boden") AND !contains(keywords, "Fliegend (Boden)")
SORT sterne DESC
```