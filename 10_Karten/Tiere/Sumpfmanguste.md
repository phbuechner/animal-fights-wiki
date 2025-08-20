---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Sumpfmanguste
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 039"
erweiterung: ""
stärke: 2
verteidigung: 1
gesundheit: 2
agilität: 5
ausdauer: 4
ap: 2
habitat: ["Feuchtgebiet"]
heimvorteil_effekt: "Erhält +1 Agilität und du darfst den Würfelwurf für Ausweichen-Reaktionen wiederholen."
anpassungen: ["Wasser"]
klimazone: ["Tropisch"]
keywords: ["Klein", "Fleischfresser", "Boden", "Schwimmend", "Tagaktiv"]
tags:
  - tierkarte
---

# Sumpfmanguste

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Kolonie (Manguste)]]
- [[Heimvorteil]]
	- Effekt:: Erhält +1 Agilität und du darfst den Würfelwurf für Ausweichen-Reaktionen wiederholen.
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Gegner dürfen ihre Angriffswürfe gegen dieses Tier nicht wiederholen.


## Spezialaktion

- **[[Ausspähen]]** (1 AP)

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