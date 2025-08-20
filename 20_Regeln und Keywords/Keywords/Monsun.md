---
typ: "Keyword"
tags:
  - terrain-keyword
  - klimazone
---

# Monsun

**Monsun** ist ein spezielles [[Terrain-Keyword]], das die Bedingungen während einer starken Regenzeit simuliert. Es beeinflusst sowohl das Gelände als auch das [[Klimazonen|Klima]].

## Regeln
- **Reduzierter Angriffsschaden:** Alle Angriffe verursachen pauschal **1 Schaden weniger** (Minimum 1).
- **Erhöhte Aktionskosten:** Jede Spezialaktion (eine Aktion, die [[AP]] kostet) kostet zusätzlich **1 Ausdauer**.

---
## Arenen mit diesem Terrain/Klima

```dataview
TABLE
  sterne as "★",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Monsun") OR contains(klima, "Monsun")
SORT sterne DESC