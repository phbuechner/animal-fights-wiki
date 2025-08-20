---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Die brennende Sonne von Tsavo
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 105
erweiterung: ""
habitat:
  - Trockengebiet
terrain_keywords:
  - Offenes Gelände
klima:
  - Extreme Hitze
tags:
  - arenakarte
---

# Die brennende Sonne von Tsavo

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Alle Tiere regenerieren am Rundenende nur 1 Ausdauer (statt der üblichen 2). [[Extreme Hitze]]*

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
WHERE heimvorteil_effekt AND contains(habitat, "Trockengebiet")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Offenes Gelände"], p))
SORT file.name ASC
