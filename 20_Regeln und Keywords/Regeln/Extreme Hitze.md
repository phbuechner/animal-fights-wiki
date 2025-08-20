---
typ: "Regel-Effekt"
tags:
  - regelwerk
---

# Extreme Hitze

**Extreme Hitze** ist ein globaler Effekt, der oft in Arenen mit [[Arid|aridem Klima]] auftritt und die [[Ausdauer]] aller Tiere stark beeinträchtigt.

## Regeln
- **Reduzierte Regeneration:** Am Ende jeder Runde regenerieren alle Tiere nur **1 Ausdauer** (statt der üblichen 2).
- **Erhöhte Angriffskosten:** Jedes Mal, wenn ein Tier eine Angriff-Aktion deklariert, verliert es zusätzlich **1 Ausdauer**.

---
## Arenen mit diesem Effekt

```dataview
TABLE
  file.link as "Arena",
  sterne as "★",
  habitat as "Habitat",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(klima, "Extreme Hitze")
SORT sterne DESC