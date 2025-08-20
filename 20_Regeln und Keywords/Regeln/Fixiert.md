---
typ: "Status-Effekt"
tags:
  - status-effekt
  - negativ
---

# Fixiert

**Fixiert** ist ein negativer [[Fortwährende Effekte & Spielzustand|Zustand]], der ein Tier zu einem leichten Ziel macht.

## Regeln
- Ein fixiertes Tier kann nicht den Zustand [[Tarnung]] erhalten.
- Es kann nicht durch Eigenschaften oder Instinktkarten vom Spielfeld entfernt werden (z.B. durch "Panik-Sprung" auf die Hand zurückkehren).

---
### Karten, die "Fixiert" verursachen
```dataview
TABLE WITHOUT ID
  file.link as "Quelle",
  typ as "Typ"
FROM #tierkarte OR #instinktkarte
WHERE contains(file.outlinks.display, "Fixiert") OR contains(file.lists.text, "Fixiert")
SORT typ ASC