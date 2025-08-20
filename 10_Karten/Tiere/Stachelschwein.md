---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Stachelschwein
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 038"
stärke: 1
verteidigung: 5
gesundheit: 2
agilität: 3
ausdauer: 4
ap: 2
habitat: ["Savanne", "Trockengebiet"]
anpassungen: ["Unterholz", "Höhle"]
klimazone: ["Arid"]
keywords:
  - Klein
  - Pflanzenfresser
  - Boden
  - Grabend
  - Nachtaktiv
tags:
  - tierkarte
---

# Stachelschwein

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |
## Eigenschaften

- **[[Vergeltung]] (2)**
- [[Anpassung (Höhle)]]
	- Anpassung:: Höhle
	- Effekt:: Kann von jedem Tier nur einmal pro Runde angegriffen werden.
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Kann von jedem Tier nur einmal pro Runde angegriffen werden.

## Spezialaktion

- **[[Verteidigungshaltung]] (1)** (1 AP)
- **[[Knochen nagen]]** (1 AP)

## Strategische Notizen & Synergien

-
