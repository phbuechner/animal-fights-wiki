---
typ: "Status-Effekt"
tags:
  - status-effekt
  - negativ
---

# Vergiftet (X)

**Vergiftet** ist ein negativer [[Fortwährende Effekte & Spielzustand|Zustand]], der über mehrere Runden hinweg wiederkehrenden Schaden verursacht und sich aufsummieren kann.

## Regeln & Effekte

- **Direkter Schaden:** Ein Tier mit dem Zustand `Vergiftet (X)` erleidet am Ende des Zuges seines Besitzers **X direkten Schaden**.
- **Stapelbar:** Wenn ein Tier, das bereits `Vergiftet (X)` ist, erneut `Vergiftet (Y)` erleiden würde, werden die Werte addiert. Der neue Zustand ist dann `Vergiftet (X + Y)`.
    - *Beispiel: Ein Tier mit `Vergiftet (1)` erleidet `Vergiftet (1)`. Sein neuer Zustand ist `Vergiftet (2)`.*
- **Dauer:** Der Zustand bleibt bestehen, bis er durch einen Karteneffekt aktiv entfernt wird.

---
### Karten, die den "Vergiftet"-Zustand verursachen

Die folgende Tabelle listet automatisch alle Karten auf, die in ihrem Regeltext oder ihren Effekten den Zustand "Vergiftet" erwähnen oder verursachen.

```dataview
TABLE WITHOUT ID
  file.link as "Quelle",
  typ as "Typ",
  sterne as "★"
FROM #tierkarte OR #instinktkarte OR #arenakarte
WHERE contains(file.outlinks.display, "Vergiftet") OR contains(file.lists.text, "Vergiftet")
SORT typ ASC