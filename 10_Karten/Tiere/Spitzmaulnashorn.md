---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 4
name: Spitzmaulnashorn
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 003
erweiterung: ""
stärke: 8
verteidigung: 7
gesundheit: 9
agilität: 3
ausdauer: 6
ap: 2
habitat: ["Trockengebiet", "Savanne"]
heimvorteil_effekt: ""
anpassungen: ["Engpass"]
klimazone: ["Arid"]
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Spitzmaulnashorn

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Engpass)]]
	- Anpassung:: Engpass
	- Effekt:: Erhält +2 Stärke
- [[Ansturm]] (2)
	- Ansturm:: 2
- [[Panzer]] (2)
	- Panzer:: 2

## Spezialaktion

- [[Überrennen]] (2 AP)

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