---
typ: Tierkarte
deck_typ: ""
sterne: 2
name: Scherenschnabel
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 029
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 6
ausdauer: 5
ap: 2
habitat: ["Feuchtgebiet"]
heimvorteil_effekt: ""
anpassungen: ["Wasser", "Flussufer", "Sumpf", "Überschwemmt"]
klimazone: ["Tropisch"]
keywords: ["Mittel", "Fleischfresser", "Fliegend", "Boden", "Dämmerungsaktiv"]
tags:
  - tierkarte
---

# Scherenschnabel

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Erhält [[Kielschnitt-Jagd]]
- [[Anpassung (Flussufer)]]
	- Anpassung:: Flussufer
	- Effekt:: Erhält [[Kielschnitt-Jagd]]
- [[Anpassung (Sumpf)]]
	- Anpassung:: Sumpf
	- Effekt:: Erhält [[Kielschnitt-Jagd]]
- [[Anpassung (Überschwemmt)]]
	- Anpassung:: Überschwemmt
	- Effekt:: Erhält [[Kielschnitt-Jagd]]
- [[Fokussierte Jagd]]



## Spezialaktion

- **[[Terrain Erkunden]]** (1 AP)

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