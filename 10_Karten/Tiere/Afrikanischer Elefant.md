---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 4
name: Afrikanischer Elefant
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 001"
stärke: 7
verteidigung: 7
gesundheit: 12
agilität: 2
ausdauer: 8
ap: 2
habitat: ["Trockengebiet", "Savanne"]
anpassungen: ["Wasser"]
klimazone: ["Arid"]
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
  - 4-sterne
  - elefant
---

# [[Afrikanischer Elefant]]

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (c) => "[[" + c + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Elefant)]]
- [[Panzer]]
	- Panzer:: 1
- [[Unermüdlich]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Voraussicht]]

## Spezialaktion

- [[Trampeln]] (2) (kostet 2 AP)

## Strategische Notizen & Synergien

- ...

%%
Habitat: [[Trockengebiet]], [[Savanne]]
Klimazone: [[Arid]]
Keywords: [[Gigantisch]], [[Pflanzenfresser]], [[Boden]], [[Tagaktiv]]
%%
---
