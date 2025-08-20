---
typ: Tierkarte
deck_typ: ""
sterne: 4
name: Nilkrokodil
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 004
erweiterung: ""
stärke: 6
verteidigung: 5
gesundheit: 8
agilität: 2
ausdauer: 5
ap: 2
habitat:
  - Feuchtgebiet
heimvorteil_effekt: Erhält Jäger aus dem Schatten
anpassungen: []
klimazone:
  - Tropisch
  - Arid
keywords:
  - Groß
  - Fleischfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Nilkrokodil

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Amphibisch]]
- [[Lauerjäger]]
- [[Heimvorteil]]
	- Effekt:: Erhält [[Jäger aus dem Schatten]]
- [[Panzer]] (1)
	- Panzer:: 1


## Spezialaktion

- **[[Beute sichern]]** (1 AP)
- **[[Todesrolle]]** (2 AP)
	- Effekt:: [[Festgehalten]]

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