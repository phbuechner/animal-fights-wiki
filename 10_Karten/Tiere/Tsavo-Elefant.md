---
typ: Tierkarte
deck_typ: Persönlich
sterne: 4
name: Tsavo-Elefant
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 002
erweiterung: ""
stärke: 8
verteidigung: 6
gesundheit: 10
agilität: 3
ausdauer: 7
ap: 2
habitat:
  - Savanne
  - Trockengebiet
anpassungen:
  - Unterholz
klimazone:
  - Arid
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
  - 4-Sterne
  - elefant
---

# Tsavo-Elefant

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Unvergesslicher Zorn]]
- [[Resistenz]] ([[Einschüchterung]])
- [[Anpassung (Unterholz)]]
	- Anpassung:: Unterholz
	- Effekt:: Ignoriert negative Effekte von Unterholz-Arenen und fügt dem Angreifer 1 direkten Schaden zu, wenn du abwehrst.

## Spezialaktion

- [[Groll hegen]] (1 AP)

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