---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Massai-Strauß
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 020"
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 6
ausdauer: 5
ap: 2
habitat: ["Savanne", "Trockengebiet"]
heimvorteil_effekt: "Erhält +1 Stärke, +1 Verteidigung und +1 AP"
anpassungen: ["Offenes Gelände"]
klimazone: ["Arid"]
keywords:
  - Groß
  - Allesfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Massai-Strauß

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzelgänger]]**
- **[[Heimvorteil]]**
	- **Effekt**:: Erhält +1 Stärke, +1 Verteidigung und +1 AP
- [[Anpassung (Offenes Gelände)]]
	- Anpassung:: Offenes Gelände
	- **Effekt**:: Die Abwehren-Aktion kostet 0 Ausdauer.

## Spezialaktion

- **[[Überrennen]]** (1 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
--- 