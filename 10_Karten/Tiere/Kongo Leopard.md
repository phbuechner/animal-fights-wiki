---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Kongo Leopard
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 010
erweiterung: ""
stärke: 5
verteidigung: 2
gesundheit: 4
agilität: 6
ausdauer: 5
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
  - Fleischfresser
  - Boden
  - Kletternd
  - Nachtaktiv
tags:
  - tierkarte
---

# Kongo Leopard

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Lauerjäger]]
- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Jäger aus dem Schatten]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Jäger aus dem Schatten]]


## Spezialaktion

- **[[Schattenflucht]]** (2 AP)

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