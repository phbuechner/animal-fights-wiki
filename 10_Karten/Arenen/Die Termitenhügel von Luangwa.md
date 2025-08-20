---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Die Termitenhügel von Luangwa
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 110
erweiterung: ""
habitat:
  - Savanne
terrain_keywords:
  - Höhenlage
  - Deckung
klima:
  - Arid
tags:
  - arenakarte
---

# Die Termitenhügel von Luangwa

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Einmal pro Runde kann ein Spieler ein eigenes Tier bestimmen. Dieses Tier kann bis zum Beginn seines nächsten Zuges nicht als Ziel von Angriffen gewählt werden, kann aber auch nicht angreifen. [[Deckung (Keyword)|Deckung]]*

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
WHERE anpassungen AND any(anpassungen, (p) => contains(["Höhenlage", "Deckung"], p))
SORT file.name ASC
