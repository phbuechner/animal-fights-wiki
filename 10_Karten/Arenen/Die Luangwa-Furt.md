---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Die Luangwa-Furt
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 041"
habitat:
  - Feuchtgebiet
terrain_keywords:
  - Wasser
  - Flussufer
  - Engpass
klima:
  - Tropisch
tags:
  - arenakarte
---

# Die Luangwa-Furt  

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Tiere können in dieser Arena die Ausweichen-Aktion nicht wählen. Am Ende jeder Runde, wenn ein Tier in diesem Zug nicht angegriffen hat, erleidet es 1 direkten Schaden.*

---
## Strategische Überlegungen


## Tiere mit Heimvorteil  
```dataview 
TABLE
  sterne as "Sterne",
  heimvorteil_effekt as "Heimvorteil Effekt"
FROM #tierkarte
WHERE heimvorteil_effekt AND contains(habitat, "Feuchtgebiet")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

```dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Wasser", "Flussufer", "Engpass"], p))
SORT file.name ASC
