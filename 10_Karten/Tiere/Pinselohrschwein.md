---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Pinselohrschwein
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 022"
erweiterung: ""
stärke: 3
verteidigung: 2
gesundheit: 4
agilität: 4
ausdauer: 5
ap: 2
habitat: ["Wald", "Feuchtgebiet"]
heimvorteil_effekt: ""
anpassungen: ["Unterholz", "Schlamm"]
klimazone: ["Tropisch"]
keywords: ["Mittel", "Allesfresser", "Boden", "Nachtaktiv"]
tags:
  - tierkarte
---

# Pinselohrschwein

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Rotte (Pinselohrschwein)]]
- [[Durchdringender Angriff]] ([[Eingeschüchtert]])
- [[Anpassung (Schlamm)]]
	- Anpassung:: Schlamm
	- Effekt:: Deine Angriffe können nicht ausgewichen werden
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält +2 Verteidigung


## Spezialaktion

- **[[Kraftangriff]] (1)** (1 AP)

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