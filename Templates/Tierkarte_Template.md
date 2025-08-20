---
typ: "Tierkarte"
deck_typ: ""
sterne: 
name: "{{title}}"
edition: ""
set_nummer: ""
erweiterung: ""
stärke: 
verteidigung: 
gesundheit: 
agilität: 
ausdauer: 
ap: 
habitat: []
heimvorteil_effekt: ""
anpassungen: []
klimazone: 
keywords: []
tags:
  - tierkarte
---

# {{title}}

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- 
[[Haupt-Fähigkeit]]
	- Schlüssel:: Wert
	-Effekt:: Der Effekttext.


## Spezialaktion

- 

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