---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Topi-Antilope
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 026"
erweiterung: ""
stärke: 2
verteidigung: 3
gesundheit: 4
agilität: 5
ausdauer: 6
ap: 2
habitat: ["Savanne"]
heimvorteil_effekt: "Erhält Wachsamkeit"
anpassungen: []
klimazone: ["Arid", "Tropisch"]
keywords: ["Mittel", "Pflanzenfresser", "Boden", "Tagaktiv"]
tags:
  - tierkarte
---

# Topi-Antilope

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Topi)]]
- [[Ausguck]]
- [[Heimvorteil]]
	- Effekt:: Erhält [[Wachsamkeit]]


## Spezialaktion

- **[[Wache halten]]** (1 AP)

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