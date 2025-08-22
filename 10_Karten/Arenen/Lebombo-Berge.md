---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Lebombo-Berge
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 114
erweiterung: ""
habitat:
  - Gebirge
terrain_keywords:
  - Felsen
  - Höhenlage
  - Schlucht
klima:
  - Arid
tags:
  - karte/arenakarte
---

# Lebombo-Berge

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Tiere können nicht durch Effekte (wie [[Versammeln]] oder [[Sammelruf]]) ins Spiel gebracht werden.*

---
## Strategische Überlegungen

*Hier ist Platz für Ihre eigenen Gedanken: Welche Decks profitieren von dieser Arena? Was kontert sie?*

---
## Tiere mit Heimvorteil

Die folgende Tabelle listet automatisch alle Tiere aus Ihrem Vault auf, deren Primär-Habitat mit dem dieser Arena übereinstimmt. Diese Tiere erhalten hier ihren "Heimvorteil"-Bonus.

```dataview
TABLE
  sterne as "Sterne",
  heimvorteil_effekt as "Heimvorteil Effekt"
FROM #tierkarte
WHERE heimvorteil_effekt AND contains(habitat, "Gebirge")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Felsen", "Höhenlage", "Schlucht"], p))
SORT file.name ASC
