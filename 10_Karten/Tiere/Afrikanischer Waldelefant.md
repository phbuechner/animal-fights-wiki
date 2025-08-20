---
typ: Tierkarte
deck_typ: ""
sterne: 4
name: Afrikanischer Waldelefant
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 001
erweiterung: ""
stärke: 6
verteidigung: 7
gesundheit: 11
agilität: 2
ausdauer: 8
ap: 2
habitat:
  - Wald
heimvorteil_effekt: ""
anpassungen: []
klimazone:
  - Tropisch
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Afrikanischer Waldelefant

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Elefant)]]
- [[Architekt des Waldes]]
- [[Dickicht-Koloss]]
- [[Panzer]] (1)
	- Panzer:: 1
	
## Spezialaktion

- [[Entwurzeln]] (2 AP)

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