---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 3
name: Verstecktes Wasserloch
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 054"
habitat:
  - Savanne
terrain_keywords:
  - Wasser
  - Offenes Gelände
  - Grasland
klima:
  - Arid
tags:
  - karte/arenakarte
---

# Verstecktes Wasserloch

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Einmal pro Runde kann ein Spieler 1 Ausdauer bezahlen, um 2 Schaden von einem seiner Tiere zu heilen. Tiere mit [[Anpassung (Wasser)]] können diesen Effekt kostenlos nutzen.*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Wasser", "Offenes Gelände", "Grasland"], p))
SORT file.name ASC
