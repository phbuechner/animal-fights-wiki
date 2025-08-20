---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Felsenpython
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 008
erweiterung: ""
stärke: 5
verteidigung: 3
gesundheit: 7
agilität: 1
ausdauer: 6
ap: 2
habitat:
  - Savanne
  - Feuchtgebiet
  - Gebirge
heimvorteil_effekt: ""
anpassungen:
  - Felsen
  - Wasser
klimazone:
  - Tropisch
  - Arid
keywords:
  - Groß
  - Schlange
  - Fleischfresser
  - Boden
  - Kletternd
  - Dämmerungsaktiv
  - Nachtaktiv
tags:
  - tierkarte
---

# Felsenpython

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Lauerjäger]]
- [[Panzer]] (1)
	- Panzer:: 1
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Felsen)]]
	- Anpassung:: Felsen
	- Effekt:: Erhält [[Tarnung]]


## Spezialaktion

- **[[Konstriktor-Angriff]]** (2 AP)
	- Effekt:: Angriff mit Schaden, Ziel erhält [[Festgehalten]]

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