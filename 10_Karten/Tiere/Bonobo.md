---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Bonobo
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 016
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 4
ap: 2
habitat:
  - Wald
heimvorteil_effekt: Erhält +1 auf Ausweich-Würfe
anpassungen: []
klimazone:
  - Tropisch
keywords:
  - Mittel
  - Allesfresser
  - Primat
  - Boden
  - Kletternd
  - Tagaktiv
tags:
  - tierkarte
---

# Bonobo

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Gemeinschaft (Bonobo)]]
- [[Sozialer Schutz]]
- [[Heimvorteil]]
	- Effekt:: Erhält +1 auf [[Ausweichen|Ausweich]]-Würfe



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