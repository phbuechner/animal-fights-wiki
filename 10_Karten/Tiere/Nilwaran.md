---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Nilwaran
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 025
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 5
agilität: 4
ausdauer: 6
ap: 2
habitat:
  - Feuchtgebiet
  - Savanne
  - Wald
heimvorteil_effekt: ""
anpassungen: []
klimazone:
  - Tropisch
  - Arid
keywords:
  - Mittel
  - Fleischfresser
  - Boden
  - Kletternd
  - Tagaktiv
tags:
  - tierkarte
---

# Nilwaran

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Amphibisch]]
- [[Aasfresser]]
	- Effekt:: Heile 1



## Spezialaktion

- [[Terrain Erkunden]] (1 AP)

## Strategische Notizen & Synergien

-

---
### Metadaten für die Graphenansicht (Unsichtbar im Lesemodus)
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---