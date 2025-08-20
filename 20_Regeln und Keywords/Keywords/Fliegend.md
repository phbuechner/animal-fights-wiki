---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
---

# Fliegend

**Fliegend** ist ein mächtiger [[Bewegungstypen|Bewegungstyp]], der Tieren große Vorteile in der Bewegung und im Kampf bietet.

## Regeln
- Fliegende Ziele sind schwer zu treffen: Angreifende [[Boden]]tiere erhalten **-2 auf ihr Angriffs-Ergebnis**.
- Diese Regel wird von Angreifern mit den Keywords [[Kletternd]] oder [[Fliegend]] ignoriert.

## Spezielle Variante
- **[[Fliegend (Boden)]]**: Eine Sonderform für flugfähige Tiere, die sich im Kampf aber wie Bodentiere verhalten.

---
### Alle Tiere mit der Fähigkeit "Fliegend"

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE (contains(keywords, "Fliegend") OR contains(keywords, "Fliegend (Boden)")) AND !contains(keywords, "Boden")
SORT agilität DESC