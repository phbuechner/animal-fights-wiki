---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Grüne Mamba
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 021
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 7
ausdauer: 5
ap: 2
habitat:
  - Wald
  - Savanne
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

# Grüne Mamba

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Durchdringender Angriff]] (Vergiftet 1)
	- Effekt:: [[Vergiftet]] (1)
- [[Anpassung (Baumkronen)]]
	- Anpassung:: Baumkronen
	- Effekt:: Erhält [[Akrobatischer Jäger]]
- [[Anpassung (Lianen)]]
	- Anpassung:: Lianen
	- Effekt:: Erhält [[Akrobatischer Jäger]]


## Spezialaktion

- 

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