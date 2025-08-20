---
typ: "Keyword"
tags:
  - keyword
  - bewegungstyp
  - zustand
  - status-effekt
  - positiv
---

# Schwimmend

**Schwimmend** ist ein spezieller [[Bewegungstypen|Bewegungstyp]], der einem Tier im Wasser mächtige defensive Boni verleiht, die einem [[Status-Effekte (Übersicht)|Zustand]] ähneln.

## Regeln & Effekte

Ein Tier mit dem Keyword "Schwimmend" erhält die folgenden Boni, solange es sich in einer Arena mit dem [[Terrain-Keyword]] [[Wasser (Keyword)|Wasser]] befindet:

- **Immunität (Direkter Schaden):** Das Tier ist immun gegen [[Direkter Schaden|direkten Schaden]].
- **Immunität (Instinktkarten):** Das Tier kann nicht als Ziel von gegnerischen [[Instinktkarten]] gewählt werden.

### Ausnahme: Amphibisch
Alle Schutz-Effekte, die ein Tier durch "Schwimmend" erhält, sind unwirksam gegen Angriffe oder Fähigkeiten von Tieren mit dem Keyword **[[Amphibisch]]**.

---
## Alle schwimmenden Tiere

```dataview
TABLE WITHOUT ID
  file.link as "Tier",
  sterne as "★",
  stärke as "S",
  verteidigung as "V"
FROM #tierkarte
WHERE contains(keywords, "Schwimmend")
SORT verteidigung DESC