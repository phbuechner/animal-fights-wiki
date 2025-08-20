---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Tsavo-Löwe
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 012"
stärke: 6
verteidigung: 3
gesundheit: 6
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Trockengebiet", "Savanne"]
anpassungen: ["Unterholz", "Trockenboden"]
klimazone: ["Arid"]
keywords:
  - Groß
  - Fleischfresser
  - Boden
  - Nachtaktiv
tags:
  - tierkarte
---

# Tsavo-Löwe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzelgänger]]**
- **[[Verfolgung]] (verliert 1 Ausdauer)** 
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält **[[Hinterhaltsexperte]]**
- [[Anpassung (Trockenboden)]]
	- Anpassung:: Trockenboden
	- Effekt:: Beendet [[Lauernd]]
	
## Spezialaktion

- **[[Verwunden]]** (2 AP)

## Strategische Notizen & Synergien

-
