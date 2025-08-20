---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Flusspferd Weibchen
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 009
erweiterung: ""
stärke: 5
verteidigung: 4
gesundheit: 7
agilität: 2
ausdauer: 6
ap: 2
habitat:
  - Feuchtgebiet
  - Savanne
heimvorteil_effekt: ""
anpassungen:
  - Wasser
klimazone:
  - Tropisch
  - Arid
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Flusspferd Weibchen

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Amphibisch]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Resistenz]] ([[Direkter Schaden]])
- [[Herde (Flusspferd)]]
- [[Vergeltung]] (1)


## Spezialaktion

- **[[Eingreifen]]** (1 AP)

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