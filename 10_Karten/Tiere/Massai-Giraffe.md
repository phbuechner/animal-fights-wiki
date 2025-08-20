---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Massai-Giraffe
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 019"
stärke: 2
verteidigung: 4
gesundheit: 7
agilität: 3
ausdauer: 6
ap: 2
habitat: ["Savanne", "Trockengebiet"]
anpassungen: ["Offenes Gelände"]
klimazone: ["Arid"]
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Massai-Giraffe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Herde (Giraffe)]]**
- **[[Wachposten]]**
- [[Anpassung (Offenes Gelände)]]
    - Anpassung:: Offenes Gelände
    - Effekt:: Kann nur von Tieren der Größenkategorie [[Groß]] oder [[Gigantisch]] angegriffen werden.


## Spezialaktion

- **[[Eingreifen]]** (2 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---