---
typ: "Regel-Konzept"
tags:
  - regelwerk
---

# Direkter Schaden

**Direkter Schaden** ist eine Form von Schaden, die nicht durch einen normalen [[Kampfablauf|Kampf]] entsteht.

## Regeln
- Direkter Schaden **ignoriert** die [[Verteidigung]]- und [[Panzer]]-Fähigkeiten des Ziels.
- Er wird direkt von der [[Gesundheit]] des Ziels abgezogen.

---
### Karten, die direkten Schaden verursachen
```dataview
TABLE WITHOUT ID
  file.link as "Quelle",
  typ as "Typ"
FROM #tierkarte OR #instinktkarte OR #arenakarte
WHERE contains(file.outlinks.display, "direkten Schaden") OR contains(file.lists.text, "direkten Schaden")
SORT typ ASC