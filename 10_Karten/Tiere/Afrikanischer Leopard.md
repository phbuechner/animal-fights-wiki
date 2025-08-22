---
typ: Tierkarte
deck_typ: Persönlich
sterne: 3
name: Afrikanischer Leopard
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 004
stärke: 4
verteidigung: 3
gesundheit: 5
agilität: 6
ausdauer: 5
ap: 2

spielweise: "Einzelgänger"
archetypen: ["Lauerjäger", "Einzelgänger"]
gruppensubtyp: ""

habitat:
  - Savanne
  - Wald
anpassungen:
  - Baumkronen
  - Höhenlage
klimazone:
  - Tropisch
keywords:
  - Groß
  - Fleischfresser
  - Boden
  - Kletternd
  - Nachtaktiv
tags:
  - tierkarte
  - 3-Sterne
---

# Afrikanischer Leopard

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger]]
- [[Lauerjäger]]
- **[[Anpassung (Höhenlage)]] / [[Anpassung (Höhenlage)]]** 
    - Anpassung:: ["Höhenlage", "Baumkronen"]
    - Effekt:: Erhält die Fähigkeit [[Hohe Warte]].

## Spezialaktion

- **[[Schattenflucht]]** (1 AP)
- **[[Durchbohrender Sprung]]** (1 AP)

## Strategische Notizen & Synergien

-

%%
Keywords: [[Groß]], [[Fleischfresser]], [[Boden]], [[Kletternd]], [[Nachtaktiv]]
Habitat: [[Wald]], [[Savanne]]
Klimazone: [[Tropisch]]
%%
---