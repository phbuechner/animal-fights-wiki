---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Gabunviper
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 019
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 4
agilität: 2
ausdauer: 5
ap: 2
habitat:
  - Wald
  - Savanne
heimvorteil_effekt: ""
anpassungen:
  - Unterholz
  - Dickicht
klimazone:
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

# Gabunviper

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Lauerjäger]]
- [[Lauert im Schatten]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Tarnung]]
- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Tarnung]]
- [[Durchdringender Angriff]] (Vergiftet (2))
	- Effekt:: [[Vergiftet]] (2)



## Spezialaktion

- **[[Unentrinnbarer Biss]]** (1 AP)

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