---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Schimpanse (Werkzeugmeister)
edition: Regenwälder & Flussdeltas
set_nummer: REAF 013
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 5
agilität: 5
ausdauer: 6
ap: 2
habitat:
  - Wald
heimvorteil_effekt: Deine Werkzeug nutzen-Aktionen kosten keine Ausdauer.
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

# Schimpanse (Werkzeugmeister)

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Gemeinschaft (Schimpanse)]]
- [[Intelligenz der Gemeinschaft]]
- [[Heimvorteil]]
	- Effekt:: Deine [[Werkzeug nutzen]]-Aktionen kosten keine Ausdauer.


## Spezialaktion

- Werkzeug greifen (1 AP): Wende [[Werkzeug nutzen]] (1, Instinkt) an.
- Umfeld gestalten (1 AP): Wende [[Werkzeug nutzen]] (1, Arena) an.

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