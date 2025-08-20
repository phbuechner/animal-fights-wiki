---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Morgennebel am Luangwa-Fluss
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 117
erweiterung: ""
habitat:
  - Feuchtgebiet
terrain_keywords:
  - Wasser
  - Dichter Nebel
  - Flussufer
klima:
  - Tropisch
tags:
  - arenakarte
---

# Morgennebel am Luangwa-Fluss

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Tiere können keine Ziele im [[Lauernd]]-Status angreifen. Am Rundenende: Jedes Tier im [[Lauernd]]-Status erleidet 1 direkten Schaden. Alle Angriffswürfe erhalten -1. ([[Dichter Nebel]])*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Wasser", "Dichter Nebel", "Flussufer"], p))
SORT file.name ASC
