---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Ngorongoro-Kraterrand
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 050"
habitat:
  - Savanne
terrain_keywords:
  - Baumkronen
  - Offenes Gelände
  - Höhenlage
klima:
  - Gemäßigt
tags:
  - arenakarte
---

# Ngorongoro-Kraterrand

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Am Ende jeder Runde, wenn du in diesem Zug kein Tier verloren hast, darfst du 1 Karte ziehen. Tiere mit der Größenkategorie [[Gigantisch]] erhalten die Eigenschaft Wachposten.*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Baumkronen", "Offenes Gelände", "Höhenlage"], p))
SORT file.name ASC
