---
typ: "Fähigkeit"
tags:
  - fähigkeit
  - keyword
---

# Lauerjäger

**Lauerjäger** ist eine Fähigkeit, die es einem Tier erlaubt, sich für einen Zug zu verstecken, um im darauffolgenden Zug einen tödlichen, vorbereiteten Angriff auszuführen.

## Zugehörige Aktion
Tiere mit dieser Fähigkeit können die folgende Grundaktion ausführen:
- **[[Lauern]] (1 AP, beendet den Zug):** Versetze dieses Tier in den Zustand [[Lauernd]].

## Strategie
Die Lauerjäger-Mechanik ist eine "High-Risk, High-Reward"-Strategie. Der Spieler opfert das Tempo eines ganzen Zuges (indem er die Aktion des Tieres beendet), um im nächsten Zug einen extrem starken und zuverlässigen Angriff zu garantieren. Sie ist besonders effektiv, um einzelne, hochwertige Ziele auszuschalten.

---
### Alle Lauerjäger

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  agilität as "A"
FROM #tierkarte
WHERE contains(keywords, "Lauerjäger")
SORT agilität DESC


