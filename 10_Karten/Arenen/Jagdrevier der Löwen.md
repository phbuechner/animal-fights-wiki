---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Jagdrevier der Löwen
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 046"
habitat:
  - Savanne
terrain_keywords:
  - Offenes Gelände
klima:
  - Gemäßigt
tags:
  - karte/arenakarte
---

# Jagdrevier der Löwen

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Am Ende deiner Runde, wenn du das Tier mit der höchsten Basis-Stärke auf dem Feld kontrollierst, regenerieren alle deine Tiere 2 Ausdauer.*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Offenes Gelände"], p))
SORT file.name ASC
