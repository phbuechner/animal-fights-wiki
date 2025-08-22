---
typ: Tierkarte
deck_typ: Persönlich
sterne: 2
name: Honigdachs
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 015
stärke: 4
verteidigung: 4
gesundheit: 3
agilität: 5
ausdauer: 7
ap: 2
spielweise: "Einzelgänger"
archetypen:
  - Allrounder
gruppensubtyp: ""
habitat:
  - Generalist
klimazone:
  - Arid
  - Tropisch
keywords:
  - Klein
  - Fleischfresser
  - Boden
  - Grabend
  - Kletternd
  - Nachtaktiv
tags:
  - tierkarte
---


| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Berserker]]**
- **[[Resistenz]] ([[Einschüchterung]]**
- **[[Zähes Fell_Zähe Schuppen_Zähe Haut|Zähes Fell]]**
- **[[Einzelgänger (Fähigkeit)|Einzelgänger]]**

## Spezialaktion

- **[[Abschütteln]]**

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---