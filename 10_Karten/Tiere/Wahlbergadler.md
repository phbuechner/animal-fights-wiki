---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Wahlbergadler
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 034
erweiterung: ""
stärke: 3
verteidigung: 2
gesundheit: 3
agilität: 5
ausdauer: 4
ap: 2
habitat: ["Generalist"]
heimvorteil_effekt: ""
anpassungen: ["Offenes Gelände", "Höhenlage"]
klimazone: ["Tropisch", "Arid", "Gemäßigt"]
keywords: ["Mittel", "Fleischfresser", "Fliegend", "Tagaktiv"]
tags:
  - tierkarte
---

# Wahlbergadler

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Offenes Gelände)]]
	- Anpassung:: Offenes Gelände
	- Effekt:: Erhält +1 Stärke
- [[Anpassung (Höhenlage)]]
	- Anpassung:: Höhenlage
	- Effekt:: Erhält +1 Stärke



## Spezialaktion

- **[[Anpassungsfähiger Jäger]]** (1 AP)

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