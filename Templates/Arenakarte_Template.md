---
typ: "Arenakarte"
deck_typ: ""
sterne: 
name: "{{title}}"
edition: ""
set_nummer: ""
erweiterung: ""
habitat: ""
terrain_keywords:
  - 
klima: ""
tags:
  - arenakarte
---

# {{title}}

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *Hier den vollständigen Regeltext der Karte einfügen. Wichtige Begriffe wie [[Dämmerungsaktiv]] oder [[Heimvorteil]] direkt verlinken.*

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
WHERE heimvorteil_effekt AND contains(habitat, "HIER_HABITAT_MANUELL_EINFÜGEN")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

``` dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains([HIER_KEYWORDS_MANUELL_EINFÜGEN], p))
SORT file.name ASC
