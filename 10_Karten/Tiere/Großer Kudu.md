---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Großer Kudu
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 006"
stärke: 3
verteidigung: 5
gesundheit: 6
agilität: 4
ausdauer: 7
ap: 2
habitat: ["Savanne", "Wald"]
heimvorteil_effekt: "Erhält Wachsamkeit."
anpassungen: ["Unterholz"]
klimazone: ["Arid"]
keywords:
  - Groß
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Großer Kudu

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzelgänger]]**
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- **Effekt**:: Erhält **[[Tarnung]]**
- **[[Heimvorteil]]**
	- **Effekt**:: Erhält **[[Wachsamkeit]]**
	
	

## Spezialaktion

- **[[Durchbrechen]]** (2 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---