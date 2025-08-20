---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Klippspringer
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 034"
erweiterung: ""
stärke: 1
verteidigung: 2
gesundheit: 2
agilität: 6
ausdauer: 4
ap: 2
habitat: ["Gebirge", "Savanne"]
heimvorteil_effekt: ""
anpassungen: []
klimazone: ["Arid"]
keywords: ["Klein", "Pflanzenfresser", "Boden", "Kletternd", "Tagaktiv"]
tags:
  - tierkarte
---

# Klippspringer

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Felsenspringer]]

## Spezialaktion

- **[[Sichere Position]]** (1 AP)

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