---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 3
name: Endlose Ebenen der Serengeti
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 043"
habitat:
  - Savanne
terrain_keywords:
  - Offenes Gelände
  - Grasland
klima:
  - Gemäßigt
tags:
  - arenakarte
---

# Endlose Ebenen der Serengeti

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Tiere können in dieser Arena die Fähigkeiten [[Lauerjäger]] oder [[Tarnung]] nicht nutzen. Am Rundenende: Wenn du 3 oder mehr Tiere einer [[Gruppierung]] kontrollierst, ziehe 1 Karte.*

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
WHERE heimvorteil_effekt AND contains(habitat, "Savanne")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Offenes Gelände", "Grasland"], p))
SORT file.name ASC
