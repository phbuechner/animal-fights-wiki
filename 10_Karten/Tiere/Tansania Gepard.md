---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Tansania Gepard
edition: Savannen Edition, Afrika Saga
set_nummer: "SHAF 001"
erweiterung: "Sprinter und Hetzer"
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 8
ausdauer: 4
ap: 2
habitat: ["Savanne", "Trockengebiet"]
heimvorteil_effekt: ""
anpassungen: []
klimazone: ["Arid"]
keywords: ["Mittel", "Fleischfresser", "Boden", "Tagaktiv"]
tags:
  - tierkarte
---

# Tansania Gepard

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Erster Schlag]]


## Spezialaktion

- **[[Sprint]]** (2 AP)

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