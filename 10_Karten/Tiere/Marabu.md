---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Marabu
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 018"
erweiterung: ""
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Feuchtgebiet", "Savanne"]
heimvorteil_effekt: "Erhält Koexistenz"
anpassungen: ["Wasser"]
klimazone: ["Tropisch"]
keywords: ["Mittel", "Boden", "Fliegend", "Tagaktiv"]
tags:
  - tierkarte
---

# Marabu

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

-[[Aasfresser]]
	- Effekt:: Heile 1
-[[Heimvorteil]]
	- Effekt:: Erhält [[Koexistenz]]
-[[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Resistenz]] ([[Direkter Schaden]])



## Spezialaktion

- [[Resteverwertung]] (1 AP)

## Strategische Notizen & Synergien

-

---
### Metadaten für die Graphenansicht (Unsichtbar im Lesemodus)
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---