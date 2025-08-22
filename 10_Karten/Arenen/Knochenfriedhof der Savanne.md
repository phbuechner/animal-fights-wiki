---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Knochenfriedhof der Savanne
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 047"
habitat:
  - Savanne
terrain_keywords:
  - Aas
  - Trockenboden
klima:
  - Arid
tags:
  - karte/arenakarte
---

# Knochenfriedhof der Savanne

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Immer, wenn ein Tier besiegt wird, darf der Besitzer eines Tieres mit [[Aasfresser 1]] Karte ziehen. Am Rundenende: Alle Tiere regenerieren 1 Ausdauer weniger (Minimum 1). Diese Arena kann nicht durch eine Arena vom allgemeinen Deck ersetzt werden.*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Aas", "Trockenboden"], p))
SORT file.name ASC
