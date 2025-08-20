---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Schuhschnabel
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 014
erweiterung: ""
stärke: 4
verteidigung: 3
gesundheit: 5
agilität: 2
ausdauer: 6
ap: 2
habitat:
  - Feuchtgebiet
heimvorteil_effekt: Erhält Lauerjäger
anpassungen: []
klimazone:
  - Tropisch
keywords:
  - Groß
  - Fleischfresser
  - Fliegend (Boden)
  - Tagaktiv
tags:
  - tierkarte
---

# Schuhschnabel

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Heimvorteil]]
	- Effekt:: Erhält [[Lauerjäger]]
- [[Stoische Geduld]]


## Spezialaktion

- **[[Blick fixieren]]** (1 AP)
- **[[Hinterhalt]]** (1 AP)

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