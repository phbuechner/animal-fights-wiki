---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Thomsongazelle
edition: Savannen Edition, Afrika Saga
set_nummer: "SHAF 004"
erweiterung: "Sprinter und Hetzer"
stärke: 1
verteidigung: 1
gesundheit: 3
agilität: 7
ausdauer: 5
ap: 2
habitat: ["Savanne", "Trockengebiet"]
heimvorteil_effekt: ""
anpassungen: ["Offenes Gelände"]
klimazone: ["Arid"]
keywords: ["Klein", "Pflanzenfresser", "Boden", "Tagaktiv"]
tags:
  - tierkarte
---

# Thomsongazelle

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Gazelle)]]
- [[Panik-Sprung]]
- [[Anpassung (Offenes Gelände)]]
	- Anpassung:: Offenes Gelände
	- Effekt:: Erhält [[Prellsprung]]

## Spezialaktion

- 

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