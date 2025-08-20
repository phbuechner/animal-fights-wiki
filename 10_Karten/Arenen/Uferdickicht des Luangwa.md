---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 2
name: Uferdickicht des Luangwa
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 052"
habitat:
  - Wald
terrain_keywords:
  - Unterholz
  - Flussufer
klima:
  - Tropisch
tags:
  - arenakarte
---

# Uferdickicht des Luangwa

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Tiere mit der Eigenschaft [[Lauerjäger]] oder [[Einzelgänger]] können nicht als Ziel von Instinktkarten des Gegners gewählt werden, solange sie nicht angegriffen haben. Alle Tiere mit dem Keyword [[Fliegend]] verlieren dieses Keyword.*

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
WHERE heimvorteil_effekt AND contains(habitat, "Wald")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Unterholz", "Flussufer"], p))
SORT file.name ASC
