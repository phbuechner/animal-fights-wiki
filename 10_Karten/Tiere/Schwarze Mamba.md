---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Schwarze Mamba
edition: Regenwälder & Flussdeltas
set_nummer: REAF 015
erweiterung: ""
stärke: 4
verteidigung: 2
gesundheit: 4
agilität: 8
ausdauer: 5
ap: 2
habitat:
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
  - Schlange
  - Boden
  - Kletternd
  - Tagaktiv
tags:
  - tierkarte
---

# Schwarze Mamba

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Ansturm]]
- [[Durchdringender Angriff]] (Vergiftet (1))
	- Durchdringender Angriff:: [[Vergiftet]] (1)]


## Spezialaktion

- **[[Drohgebärde]]** (1 AP)

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