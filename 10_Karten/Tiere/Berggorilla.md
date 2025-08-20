---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Berggorilla
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 007
erweiterung: ""
stärke: 4
verteidigung: 4
gesundheit: 6
agilität: 3
ausdauer: 6
ap: 2
habitat:
  - Wald
  - Gebirge
heimvorteil_effekt: ""
anpassungen: []
klimazone:
  - Tropisch
keywords:
  - Groß
  - Primat
  - Pflanzenfresser
  - Boden
  - Kletternd
  - Tagaktiv
tags:
  - tierkarte
---

# Berggorilla

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Gemeinschaft (Gorilla)]]
- [[Loyaler Leibwächter]]


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