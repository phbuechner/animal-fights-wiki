---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Impala
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 033"
stärke: 2
verteidigung: 1
gesundheit: 2
agilität: 6
ausdauer: 4
ap: 3
habitat: ["Savanne", "Wald"]
klimazone: ["Arid", "Tropisch"]
keywords:
  - Mittel
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Impala

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Herde (Impala)]]**
- **[[Panik-Sprung]]**
- **[[Sicherheit in der Masse]] (3)**
	- **Effekt**:: Kann nicht als Ziel von Spezialaktionen gewählt werden.

## Spezialaktion

- 

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---