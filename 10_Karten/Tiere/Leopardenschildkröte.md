---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Leopardenschildkröte
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 017"
erweiterung: ""
stärke: 1
verteidigung: 6
gesundheit: 5
agilität: 1
ausdauer: 7
ap: 2
habitat: ["Trockengebiet", "Savanne"]
heimvorteil_effekt: ""
anpassungen: ["Felsen", "Trockenboden"]
klimazone: ["Arid"]
keywords: ["Klein", "Pflanzenfresser", "Boden", "Tagaktiv"]
tags:
  - tierkarte
---

# Leopardenschildkröte

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Trockenboden)]]
	- Anpassung:: Trockenboden
	- Effekt:: Erhält +1 maximale Gesundheit
- [[Anpassung (Felsen)]]
	- Anpassung:: Felsen
	- Effekt:: Erhält [[Resistenz]] (Verteidigungs-Reduktion)
- [[Einzelgänger]]
- [[Panzer]] (2)
	- Panzer:: 2

## Spezialaktion

- [[Einigeln]] (1 AP)

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