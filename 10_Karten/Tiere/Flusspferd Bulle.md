---
typ: Tierkarte
deck_typ: ""
sterne: 4
name: Flusspferd Bulle
edition: Regenwälder & Flussdeltas
set_nummer: REAF 003
erweiterung: ""
stärke: 7
verteidigung: 5
gesundheit: 9
agilität: 2
ausdauer: 7
ap: 2
habitat:
  - Feuchtgebiet
  - Savanne
heimvorteil_effekt: ""
anpassungen: []
klimazone:
  - Tropisch
  - Arid
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Flusspferd Bulle

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzigartig]]
- [[Amphibisch]]
- Herrscher des Flusses
	- Effekt:: Wähle zu Spielbeginn eine Rolle für dieses Tier:
	  A) **Einsamer Bulle** - Erhält [[Einzelgänger]] und [[Einschüchterung]]
	  B) **Anführer des Harems** - Erhält [[Herde (Flusspferd)]] und [[Zorniger Verteidiger]]



## Spezialaktion

- **[[Wütender Tauchgang]]** (2 AP)
- **[[Territorium beanspruchen]]** (1 AP)

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