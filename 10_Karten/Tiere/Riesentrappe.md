---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Riesentrappe
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 023"
stärke: 2
verteidigung: 4
gesundheit: 5
agilität: 3
ausdauer: 5
ap: 2
habitat: ["Savanne", "Trockengebiet"]
anpassungen: ["Offenes Gelände"]
klimazone: ["Arid"]
keywords:
  - Groß
  - Allesfresser
  - Fliegend (Boden)
  - Tagaktiv
tags:
  - tierkarte
---

# Riesentrappe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzelgänger]]**
- **[[Unbeirrbare Präsenz]]**
- [[Anpassung (Offenes Gelände)]]
	- Anpassung:: Offenes Gelände
	- **Effekt**:: Erhält **[[Einschüchterung]]**

## Spezialaktion


## Strategische Notizen & Synergien

-
