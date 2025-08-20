---
typ: "Status-Effekt"
tags:
  - status-effekt
  - negativ
---

# Festgehalten

**Festgehalten** ist ein starker negativer [[Status-Effekte (Übersicht)|Zustand]], der ein Tier vorübergehend komplett handlungsunfähig macht.

## Regeln & Effekte

- **Aktionsverlust:** Ein Tier, das festgehalten ist, kann in seinem nächsten Zug **keine Aktionen** (weder Grund- noch Spezialaktionen) deklarieren.
- **Direkter Schaden:** Das Tier erleidet am Ende des Zuges, in dem es festgehalten wurde, **1 direkten Schaden**.
- **Dauer:** Der Zustand wird am Ende des Zuges, in dem das Tier keine Aktionen deklarieren konnte, wieder entfernt.

---
### Karten, die den "Festgehalten"-Zustand verursachen

Die folgende Tabelle listet automatisch alle Karten auf, die in ihrem Regeltext oder ihren Effekten den Zustand "Festgehalten" erwähnen oder verursachen.

```dataview
TABLE WITHOUT ID
  file.link as "Quelle",
  typ as "Typ",
  sterne as "★"
FROM #tierkarte OR #instinktkarte OR #arenakarte
WHERE contains(file.outlinks.display, "Festgehalten") OR contains(file.lists.text, "Festgehalten")
SORT typ ASC