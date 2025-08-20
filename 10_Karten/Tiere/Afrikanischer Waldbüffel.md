---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Afrikanischer Waldbüffel
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 006
erweiterung: ""
stärke: 5
verteidigung: 4
gesundheit: 6
agilität: 3
ausdauer: 6
ap: 2
habitat:
  - Wald
heimvorteil_effekt: ""
anpassungen:
  - Dickicht
  - Unterholz
klimazone:
  - Tropisch
keywords:
  - Groß
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Afrikanischer Waldbüffel

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Ansturm]] (2)
	- Ansturm:: 2
- [[Herde (Kaffernbüffel)]]
- [[Berserker]]
- [[Anpassung (Dickicht)]]
	- Anpassung:: Dickicht
	- Effekt:: Erhält [[Durchbruch]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Durchbruch]]



## Spezialaktion

- **[[Überrennen]]** (2 AP)

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