---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Ufer des Kazinga-Kanals
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 051"
habitat:
  - Feuchtgebiet
terrain_keywords:
  - Wasser
  - Flussufer
  - Offenes Gelände
klima:
  - Tropisch
tags:
  - karte/arenakarte
---

# Ufer des Kazinga-Kanals

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Solange du mehr Tiere kontrollierst als dein Gegner, erhalten deine Tiere [[Sicherheit in der Masse]] (1).*

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
WHERE heimvorteil_effekt AND contains(habitat, "Feuchtgebiet")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Wasser", "Flussufer", "Offenes Gelände"], p))
SORT file.name ASC
