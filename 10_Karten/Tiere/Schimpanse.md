---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Schimpanse
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 011"
stärke: 4
verteidigung: 3
gesundheit: 5
agilität: 6
ausdauer: 5
ap: 2
habitat: ["Wald", "Savanne"]
klimazone: ["Tropisch"]
keywords:
  - Mittel
  - Allesfresser
  - Boden
  - Kletternd
  - Tagaktiv
  - Primat
tags:
  - tierkarte
---

# Schimpanse

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Gemeinschaft (Schimpanse)]]**
- **[[Kooperative Jagd]]**

## Spezialaktion

- **[[Dominanz zeigen]]** (2 AP)
- **[[Werkzeug nutzen]] (1, Instinkt)** (1 AP)

## Strategische Notizen & Synergien

-
