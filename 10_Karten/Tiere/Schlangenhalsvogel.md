---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Schlangenhalsvogel
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 030
erweiterung: ""
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 5
ausdauer: 6
ap: 1
habitat: ["Feuchtgebiet", "Wald"]
heimvorteil_effekt: ""
anpassungen: ["Wasser", "Sumpf"]
klimazone: ["Tropisch"]
keywords: ["Groß", "Fleischfresser", "Kletternd", "Fliegend", "Tagaktiv"]
tags:
  - tierkarte
---

# Schlangenhalsvogel

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Amphibisch]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Tarnung]] und [[Tiefer Tauchgang]]
- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Tarnung]] und [[Tiefer Tauchgang]]
- [[Durchbruch]]
- [[Wasserlog-Gefieder]]

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