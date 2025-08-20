---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Boomslang
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 018
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 5
ausdauer: 6
ap: 2
habitat:
  - Savanne
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Baumkronen
  - Lianen
klimazone:
  - Tropisch
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

# Boomslang

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Baumkronen)]]
	- Anpassung:: Baumkronen
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Lianen)]]
	- Anpassung:: Lianen
	- Effekt:: Erhält [[Tarnung]]
- [[Hämotoxin]]



## Spezialaktion

- **[[Beobachten]]** (1 AP)

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