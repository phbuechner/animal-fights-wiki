---
typ: Tierkarte
deck_typ: Persönlich
sterne: 2
name: Wollkopfgeier
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 031
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 4
ausdauer: 4
ap: 2
habitat:
  - Savanne
  - Trockengebiet
  - Gebirge
anpassungen:
  - Aas
klimazone:
  - Arid
  - Tropisch
keywords:
  - Mittel
  - Fleischfresser
  - Fliegend (Boden)
  - Tagaktiv
tags:
  - tierkarte
---

# Wollkopfgeier

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Schwarm (Geier)]]**
- **[[Ansturm]] (1)**
- [[Anpassung (Aas)]]
	- Anpassung:: Aas
	- Effekt:: Erhalte +1 Ausdauer
- **[[Aasfresser]]**
	- **Effekt**:: Du darfst den nächsten Initiative-Wurf dieses Tieres wiederholen


## Spezialaktion

- **[[Drohflug]]** (1 AP)

## Strategische Notizen & Synergien

-
