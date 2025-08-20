---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Senegal-Schirrantilope
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 032
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 6
ausdauer: 5
ap: 2
habitat:
  - Wald
  - Savanne
heimvorteil_effekt: ""
anpassungen:
  - Dickicht
  - Unterholz
klimazone:
  - Tropisch
keywords:
  - Mittel
  - Pflanzenfresser
  - Boden
  - Nachtaktiv
tags:
  - tierkarte
---

# Senegal-Schirrantilope

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Tarnung]]
- [[Panik-Sprung]]
- [[Finte]]


## Spezialaktion

- **[[Vom Gejagten zum Jäger]]** (1 AP)

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