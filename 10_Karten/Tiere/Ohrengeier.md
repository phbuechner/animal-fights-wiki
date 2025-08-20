---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Ohrengeier
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 010"
stärke: 3
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Trockengebiet", "Savanne", "Gebirge"]
anpassungen: ["Aas"]
klimazone: ["Arid"]
keywords:
  - Mittel
  - Fleischfresser
  - Fliegend (Boden)
  - Tagaktiv
tags:
  - tierkarte
---

# Ohrengeier

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Schwarm (Geier)]]**
- **[[Aasfresser]]**
	- **Effekt**:: Erhalte +1 auf den nächsten [[Gnadenstoß]]
- **[[Dominanz am Aas]]**
- [[Anpassung (Aas)]]
	- Anpassung:: Aas
	- Effekt:: Erhalte **[[Einschüchterung]]**
- 

## Spezialaktion

- **[[Panzerbrecher]]** (1 AP)
- **[[Gnadenstoß]] (2)** (1 AP)

## Strategische Notizen & Synergien

-
