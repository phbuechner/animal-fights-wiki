---
typ: "Status-Effekt"
tags:
  - status-effekt
  - negativ
---

# Eingeschüchtert

**Eingeschüchtert** ist ein negativer [[Status-Effekte (Übersicht)|Zustand]], der die offensive Schlagkraft eines Tieres erheblich reduziert.

## Regeln
Ein Tier, das eingeschüchtert ist:
- kann keine **Spezialaktionen** ausführen.
- verursacht mit seinen Angriffen **1 Schaden weniger**.
- Der Zustand hält für eine Runde an.

---
### Fähigkeiten, die "Einschüchterung" verursachen

Die Eigenschaft **[[Einschüchterung]]** erlaubt es einem Tier, einen [[Einschüchterung-Test]] zu starten, um diesen Zustand zu verursachen.

---
### Karten, die den "Eingeschüchtert"-Zustand verursachen

Die folgende Tabelle listet automatisch alle Karten auf, die in ihrem Regeltext oder ihren Effekten den Zustand "Eingeschüchtert" erwähnen oder verursachen.

```dataview
TABLE WITHOUT ID
  file.link as "Quelle",
  typ as "Typ"
FROM #tierkarte OR #instinktkarte OR #arenakarte
WHERE contains(file.outlinks.display, "Eingeschüchtert") OR contains(file.lists.text, "Eingeschüchtert")
SORT typ ASC