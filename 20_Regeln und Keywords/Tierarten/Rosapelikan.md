---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Rosapelikan
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 028
erweiterung: ""
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Feuchtgebiet"]
heimvorteil_effekt: ""
anpassungen: ["Wasser"]
klimazone: ["Tropisch", "Arid"]
keywords: ["Mittel", "Fleischfresser", "Fliegend (Boden)", "Tagaktiv"]
tags:
  - tierkarte
---

# Rosapelikan

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Schwarm (Pelikan)]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Kooperative Jagd]]


## Spezialaktion

- **[[Versammeln]]** (2 AP)

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