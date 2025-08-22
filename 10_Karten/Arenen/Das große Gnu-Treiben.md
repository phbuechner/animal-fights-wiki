---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Das große Gnu-Treiben
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 104
erweiterung: ""
habitat:
  - Savanne
terrain_keywords:
  - Grasland
klima:
  - Gemäßigt
tags:
  - karte/arenakarte
---

# Das große Gnu-Treiben

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Zu Beginn der Initiativphase müssen alle Tiere mit der Eigenschaft [[Rudel]] oder [[Archetyp - Herde]] einen W6 würfeln. Bei einer 1 können sie in dieser Runde nicht angreifen..*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Grasland"], p))
SORT file.name ASC
