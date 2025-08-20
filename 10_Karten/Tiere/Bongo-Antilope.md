---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Bongo-Antilope
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 005"
erweiterung: ""
stärke: 3
verteidigung: 4
gesundheit: 5
agilität: 4
ausdauer: 7
ap: 2
habitat: ["Wald"]
heimvorteil_effekt: "Erhält Resistenz (Agilitäts-Reduktion)"
anpassungen: ["Unterholz"]
klimazone: ["Tropisch"]
keywords: ["Groß", "Pflanzenfresser", "Boden", "Dämmerungsaktiv"]
tags:
  - tierkarte
---

# Bongo-Antilope

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Erhält [[Tarnung]].
- [[Heimvorteil]]
	- Effekt:: Erhält Resistenz (Agilitäts-Reduktion)


## Spezialaktion

- **[[Spähen]] (3, Arena)** (1 AP)

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