---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 3
name: Weitläufiges Jagdrevier
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 056"
habitat:
  - Savanne
terrain_keywords:
  - Offenes Gelände
  - Grasland
  - Trockenboden
klima:
  - Gemäßigt
tags:
  - arenakarte
---

# Weitläufiges Jagdrevier

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Alle Tiere erhalten +1 Agilität. Einmal pro Runde kann ein Spieler 1 Ausdauer bezahlen, damit der nächste Angriff eines seiner Tiere in diesem Zug nicht ausgewichen werden kann.*

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
