---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Riesenwaldschwein
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 012
erweiterung: ""
stärke: 4
verteidigung: 4
gesundheit: 8
agilität: 2
ausdauer: 6
ap: 2
habitat:
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Unterholz
  - Dickicht
klimazone:
  - Tropisch
keywords:
  - Groß
  - Allesfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Riesenwaldschwein

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Rotte (Riesenwaldschwein)]]
- [[Panzer]] (1)
	- Panzer:: 1
- [[Vergeltung]] (1)
	- Vergeltung:: 1
- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Durchbruch]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Durchbruch]]



## Spezialaktion

- **[[Verteidigungshaltung]] (2)** (1 AP)

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