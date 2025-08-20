---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Schabrackenschakal
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 036"
stärke: 2
verteidigung: 1
gesundheit: 3
agilität: 5
ausdauer: 4
ap: 2
habitat: ["Trockengebiet", "Savanne"]
anpassungen: ["Aas"]
klimazone: ["Arid"]
keywords:
  - Klein
  - Fleischfresser
  - Boden
  - Nachtaktiv
tags:
  - tierkarte
---

# Schabrackenschakal

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Rudel (Schabrackenschakal)]]**
- [[Anpassung (Aas)]]
	- Anpassung:: Aas
	- **Effekt**:: Erhält +1 Stärke
- **[[Aasfresser]]**
	- **Effekt**:: Regeneriere 2 Ausdauer 

## Spezialaktion

- **[[Schwäche ausnutzen]]** (2 AP)

## Strategische Notizen & Synergien

-
