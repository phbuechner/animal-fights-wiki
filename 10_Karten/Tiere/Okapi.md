---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Okapi
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 026
erweiterung: ""
stärke: 1
verteidigung: 4
gesundheit: 5
agilität: 3
ausdauer: 5
ap: 1
habitat:
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Unterholz
  - Dickicht
klimazone:
  - Tropisch
keywords:
  - Groß
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Okapi

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Tarnung]]
- [[Scheues Wesen]]



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