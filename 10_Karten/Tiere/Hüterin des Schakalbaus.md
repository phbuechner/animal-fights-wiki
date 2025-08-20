---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Hüterin des Schakalbaus
edition: Savannen Edition, Afrika Saga
set_nummer: "SHAF 002"
erweiterung: "Sprinter und Hetzer"
stärke: 2
verteidigung: 2
gesundheit: 4
agilität: 6
ausdauer: 4
ap: 2
habitat: ["Savanne", "Trockengebiet"]
heimvorteil_effekt: ""
anpassungen: []
klimazone: ["Arid"]
keywords: ["Klein", "Fleischfresser", "Boden", "Nachtaktiv"]
tags:
  - tierkarte
---

# Hüterin des Schakalbaus

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzigartig]]
- [[Rudel (Schabrackenschakal)]]
- [[Wachposten]]


## Spezialaktion

- **[[Warnruf]]** (1 AP)

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