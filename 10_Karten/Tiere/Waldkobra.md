---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Waldkobra
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 035
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Wald", "Feuchtgebiet"]
heimvorteil_effekt: ""
anpassungen: []
klimazone: ["Tropisch"]
keywords: ["Mittel", "Fleischfresser", "Schlange", "Boden", "Kletternd", "Tagaktiv"]
tags:
  - tierkarte
---

# Waldkobra

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einschüchterung]]
- [[Durchdringender Angriff]] (Vergiftet (1))
	- Durchdringender Angriff:: [[Vergiftet]] (1)
- [[Aufgerichtete Haube]]


## Spezialaktion

- **[[Listiger Vorstoß]]** (1 AP)

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