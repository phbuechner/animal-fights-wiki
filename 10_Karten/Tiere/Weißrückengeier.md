---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Weißrückengeier
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 030"
stärke: "2"
verteidigung: 2
gesundheit: 5
agilität: 4
ausdauer: 6
ap: 2
habitat: ["Savanne", "Gebirge"]
anpassungen: ["Höhenlage"]
klimazone: ["Arid"]
keywords:
  - Mittel
  - Fleischfresser
  - Fliegend (Boden)
  - Tagaktiv
tags:
  - tierkarte
---

# Weißrückengeier

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |
## Eigenschaften

- **[[Schwarm (Geier)]]**
- [[Anpassung (Höhenlage)]]
	- Anpassung:: Höhenlage
	- **Effekt**:: Du darfst einmal pro Runde die Handkarten des Gegners ansehen.
- **[[Aasfresser]]** 
	- **Effekt**:: Heile 2


## Spezialaktion

- **[[Ausspähen]]** (1 AP)

## Strategische Notizen & Synergien

-
