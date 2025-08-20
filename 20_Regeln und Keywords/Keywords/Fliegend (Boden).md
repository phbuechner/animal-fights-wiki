---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
---

# Fliegend (Boden)

**Fliegend (Boden)** ist eine spezielle Variante des [[Fliegend]]-Keywords.

## Regeln
- Tiere mit diesem Keyword gelten als **Fliegend**.
- Sie profitieren **nicht** von dem defensiven Malus gegen angreifende [[Boden]]tiere.
- Ihre "Ausweichen"-Reaktion kostet zusätzlich **+1 Ausdauer**.

---
### Alle Tiere mit der Fähigkeit "Fliegend (Boden)"

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Fliegend (Boden)")
SORT agilität DESC
