---
typ: Tierkarte
deck_typ: ""
sterne: 4
name: Berggorilla Silberrücken
edition: Regenwälder & Flussdeltas
set_nummer: REAF 002
erweiterung: ""
stärke: 5
verteidigung: 5
gesundheit: 8
agilität: 3
ausdauer: 8
ap: 2
habitat:
  - Wald
  - Gebirge
heimvorteil_effekt: ""
anpassungen: []
klimazone:
  - Tropisch
keywords:
  - Groß
  - Primat
  - Pflanzenfresser
  - Boden
  - Kletternd
  - Tagaktiv
tags:
  - tierkarte
---

# Berggorilla Silberrücken

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzigartig]]
- [[Einschüchterung]]
- [[Panzer]] (1)
	- Panzer:: 1
- [[Silberrücken]]
	- Effekt:: Wähle zu Spielbeginn eine Rolle für dieses Tier: 
	  A) [[Einsamer Wanderer]] - Erhält [[Einzelgänger]], [[Resistenz]] ([[Einschüchterung]] & [[Festgehalten]]) 
	  B) [[Patriarch]] - Erhält [[Gemeinschaft (Gorilla)]] & [[Beschützer]] (4)


## Spezialaktion

- **[[Brusttrommeln]]** (2 AP)
- **[[Herausforderung]] (3)** (1 AP)

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