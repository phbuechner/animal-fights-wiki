---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Puffotter
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 027
erweiterung: ""
stärke: 2
verteidigung: 4
gesundheit: 5
agilität: 1
ausdauer: 5
ap: 2
habitat:
  - Savanne
  - Trockengebiet
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Unterholz
  - Dickicht
klimazone:
  - Arid
  - Tropisch
keywords:
  - Mittel
  - Fleischfresser
  - Schlange
  - Boden
  - Nachtaktiv
tags:
  - tierkarte
---

# Puffotter

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Dickicht) ]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Unterholz)]] 
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Tarnung]]
- [[Zähes Fell_Zähe Schuppen|Zähe Schuppen]]
- [[Vergeltung]]
	- Vergeltung:: [[Vergiftet]] (1)

## Spezialaktion

- **[[Gift anreichern]]** (1 AP)

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