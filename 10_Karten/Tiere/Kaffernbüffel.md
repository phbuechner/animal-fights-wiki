---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Kaffernbüffel
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 007
erweiterung: ""
stärke: 4
verteidigung: 5
gesundheit: 6
agilität: 3
ausdauer: 7
ap: 2
habitat:
  - Savanne
  - Feuchtgebiet
heimvorteil_effekt: ""
anpassungen:
  - Engpass
klimazone:
  - Tropisch
  - Arid
keywords:
  - Groß
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
---

# Kaffernbüffel

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Kaffernbüffel)]]
- [[Gruppenverteidigung]] (1)
- [[Unversöhnlicher Groll]]
- [[Anpassung (Engpass)]]
	- Anpassung: Engpass
	- Effekt:: Erhält +1 Verteidigung

## Spezialaktion

- [[Gegenangriff]] (2 AP)

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