---
typ: Arenakarte
deck_typ: Allgemein
sterne: 0
name: Oloololo-Steilhang
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 119
erweiterung: ""
habitat:
  - Gebirge
terrain_keywords:
  - Felsen
  - Höhenlage
klima:
  - Gemäßigt
tags:
  - arenakarte
---

# Oloololo-Steilhang

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Jedes Mal, wenn ein Tier einen Ausweich-Wurf nicht schafft, erleidet es sofort 1 zusätzlichen Schaden durch den Sturz.*

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
WHERE heimvorteil_effekt AND contains(habitat, "Gebirge")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Felsen", "Höhenlage"], p))
SORT file.name ASC
