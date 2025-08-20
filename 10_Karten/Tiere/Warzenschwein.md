---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Warzenschwein
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 028"
stärke: "3"
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 6
ap: 2
habitat: ["Savanne", "Trockengebiet"]
anpassungen: ["Schlamm", "Höhle"]
klimazone: ["Arid"]
keywords:
  - Mittel
  - Allesfresser
  - Boden
  - Grabend
  - Tagaktiv
tags:
  - tierkarte
---

# Warzenschwein

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Ansturm]] (1)**
- [[Anpassung (Schlamm)]]
	- Anpassung:: Schlamm
	- Effekt:: Wenn du deinen Zug beendest und nicht angegriffen wurdest, heile 1 Schaden.
- [[Anpassung (Höhle)]]
	- Anpassung:: Höhle
	- **Effekt**:: Erhält **[[Vergeltung]] (1)**
- **[[Letzter Wille]]**
	- **Effekt**:: Ziehe 1 Karte



## Spezialaktion

- **[[Aufwühlen]]** (1 AP)

## Strategische Notizen & Synergien

-
