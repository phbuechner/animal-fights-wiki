---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Sitatunga
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 033
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Feuchtgebiet"]
heimvorteil_effekt: ""
anpassungen: ["Sumpf", "Wasser", "Mangroven"]
klimazone: ["Tropisch"]
keywords: ["Mittel", "Pflanzenfresser", "Boden", "Dämmerungsaktiv"]
tags:
  - tierkarte
---

# Sitatunga

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Amphibisch]]
- [[Panik-Sprung]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Mangroven)]]
	- Anpassung:: Mangroven
	- Effekt:: Erhält [[Tarnung]]
## Spezialaktion

- **[[Totenstill verharren]]** (1 AP)

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