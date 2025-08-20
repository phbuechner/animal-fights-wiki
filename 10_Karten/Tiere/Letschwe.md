---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Letschwe
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 022
erweiterung: ""
stärke: 1
verteidigung: 4
gesundheit: 4
agilität: 3
ausdauer: 6
ap: 2
habitat:
  - Feuchtgebiet
heimvorteil_effekt: ""
anpassungen:
  - Wasser
  - Sumpf
klimazone:
  - Tropisch
keywords:
  - Mittel
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Letschwe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Tarnung]]
- [[Amphibisch]]
- [[Tiefer Tauchgang]]



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