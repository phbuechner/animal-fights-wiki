---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Serval
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 037"
stärke: 3
verteidigung: 1
gesundheit: 3
agilität: 5
ausdauer: 3
ap: 2
habitat: ["Savanne", "Feuchtgebiet"]
anpassungen: ["Unterholz"]
klimazone: ["Arid", "Tropisch"]
keywords:
  - Klein
  - Fleischfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Serval

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzelgänger]]**
- **[[Jäger kleiner Beute]]**
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Dein erster Angriff in jeder Runde kann nicht ausgewichen werden.

## Spezialaktion

- **[[Sprungangriff]]** (1 AP)

## Strategische Notizen & Synergien

-
