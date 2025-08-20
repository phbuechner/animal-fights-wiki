---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Tüpfelhyäne
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 027"
stärke: 3
verteidigung: 3
gesundheit: 5
agilität: 3
ausdauer: 5
ap: 2
habitat: ["Savanne", "Feuchtgebiet"]
klimazone: ["Arid"]
keywords:
  - Mittel
  - Fleischfresser
  - Boden
  - Nachtaktiv
tags:
  - tierkarte
---

# Tüpfelhyäne

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Rudel (Tüpfelhyäne)]]**
- **[[Aasfresser]]**
	- **Effekt**:: Heile 1
- **[[Zermalmender Biss]]**

## Spezialaktion

- **[[Hetzjagd]]** (1 AP)

## Strategische Notizen & Synergien

-
