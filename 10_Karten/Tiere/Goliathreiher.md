---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Goliathreiher
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 020
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 4
agilität: 2
ausdauer: 5
ap: 2
habitat:
  - Feuchtgebiet
heimvorteil_effekt: ""
anpassungen:
  - Sumpf
klimazone:
  - Tropisch
keywords:
  - Groß
  - Fleischfresser
  - Fliegend
  - Tagaktiv
tags:
  - tierkarte
---

# Goliathreiher

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Unverrückbar]]
- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Einschüchterung]]



## Spezialaktion

- **[[Revier verteidigen]]** (2 AP)

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