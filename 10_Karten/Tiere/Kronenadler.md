---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Kronenadler
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 011
erweiterung: ""
stärke: 5
verteidigung: 3
gesundheit: 4
agilität: 5
ausdauer: 5
ap: 2
habitat:
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Baumkronen
klimazone:
  - Tropisch
keywords:
  - Mittel
  - Fleischfresser
  - Fliegend
  - Tagaktiv
tags:
  - tierkarte
---

# Kronenadler

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Lauerjäger]]
- [[Anpassung (Baumkronen)]]
	- Anpassung:: Baumkronen
	- Effekt:: Erhält [[Primatenjäger]]


## Spezialaktion

- **[[Horst beziehen]]** (1 AP)

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