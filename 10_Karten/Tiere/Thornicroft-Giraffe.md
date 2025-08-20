---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Thornicroft-Giraffe
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 025"
stärke: 2
verteidigung: 4
gesundheit: 6
agilität: 3
ausdauer: 6
ap: 2
habitat: ["Feuchtgebiet", "Savanne"]
anpassungen: ["Flussufer", "Sumpf"]
heimvorteil_effekt: "Solange du mindestens eine Thornicroft-Giraffe im Spiel hast, erhalten andere Tiere deiner [[Herde (Giraffe)|Gruppierung]] +1 Verteidigung."
klimazone: ["Arid"]
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---


# Thornicroft-Giraffe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |
## Eigenschaften

- **[[Herde (Giraffe)]]**
- [[Anpassung (Flussufer)]]
	- Anpassung:: Flussufer
	- Effekt:: Erhält **[[Resistenz]]** (Ausdauer-Verlust)
- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält **[[Resistenz]]** (Ausdauer-Verlust)
- **[[Heimvorteil]]**
	- **Effekt**:: Solange du mindestens eine Thornicroft-Giraffe im Spiel hast, erhalten andere Tiere deiner [[Herde (Giraffe)|Gruppierung]] +1 Verteidigung.

## Spezialaktion

- **[[Wachsamkeit gewähren]]** (1 AP)

## Strategische Notizen & Synergien

-
