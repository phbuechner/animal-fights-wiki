---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Karakal
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 016"
stärke: 3
verteidigung: 2
gesundheit: 3
agilität: 7
ausdauer: 4
ap: 2
habitat: ["Trockengebiet", "Savanne"]
anpassungen: ["Felsen"]
klimazone: ["Arid"]
keywords:
  - Klein
  - Fleischfresser
  - Boden
  - Kletternd
  - Nachtaktiv
tags:
  - tierkarte
---

# Karakal

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |
## Eigenschaften

- **[[Lauerjäger]]**
- **[[Akrobatischer Jäger]]**
- [[Anpassung (Felsen)]]
	- Anpassung: Felsen
	- Effekt:: Erhält [[Resistenz]] (Agilitäts-Reduktion)
- 

## Spezialaktion

- **[[Durchbohrender Sprung]]** (1 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---