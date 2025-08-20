---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Oryx-Antilope
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 021"
erweiterung: ""
stärke: 3
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 6
ap: 2
habitat: ["Trockengebiet", "Savanne"]
heimvorteil_effekt: ""
anpassungen: ["Trockenboden"]
klimazone: ["Arid"]
keywords: ["Groß", "Pflanzenfresser", "Boden", "Tagaktiv"]
tags:
  - tierkarte
---

# Oryx-Antilope

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Oryx)]]
- [[Resistenz]] ([[Extreme Hitze]]-Effekte)
- [[Mutiger Verteidiger]]
- [[Anpassung (Trockenboden)]]
	- Anpassung:: Trockenboden
	- Effekt:: Regeneriert am Rundenende +1 zusätzliche Ausdauer

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