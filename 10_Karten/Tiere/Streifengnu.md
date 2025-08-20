---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Streifengnu
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 024"
stärke: "2"
verteidigung: 3
gesundheit: 4
agilität: 4
ausdauer: 6
ap: 2
habitat: ["Savanne", "Feuchtgebiet"]
heimvorteil_effekt: "Andere Tiere der Herde erhalten +1 Verteidigung."
klimazone: ["Arid"]
keywords:
  - Mittel
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
  - 2-Sterne

---



# Streifengnu

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Herde (Streifengnu)]]**
- **[[Stampede (3)]]**
	- **Effekt**:: Alle Tiere dieser Herde erhalten +1 Stärke und +1 auf alle [[Einschüchterungstests]]
- **[[Heimvorteil]]**
	- **Effekt**:: Andere Tiere der Herde erhalten +1 Verteidigung.

## Spezialaktion

- **[[Instinktives Rufen]] (Streifengnu)** (1 AP)

## Strategische Notizen & Synergien

-
