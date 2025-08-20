---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Massai-Löwe
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 008"
stärke: 5
verteidigung: 4
gesundheit: 6
agilität: 4
ausdauer: 4
ap: 2
habitat: ["Savanne", "Trockengebiet"]
heimvorteil_effekt: "Erhält +1 Ausdauer."
anpassungen: ["Offenes Gelände"]
klimazone: ["Arid"]
keywords:
  - Groß
  - Fleischfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Massai-Löwe

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- **[[Einzigartig]]**
- [[Anpassung (Offenes Gelände)]]
    - Anpassung:: Offenes Gelände
    - Effekt:: Erhält [[Einschüchterung]].
- **[[Heimvorteil]]**
	- **Effekt**:: Erhält +1 Ausdauer
- **[[König der Savanne]]** *Wähle zu Spielbeginn eine Rolle*
	- **Effekt**:: **[[Einzelgänger]]**
	- Effekt:: **[[Patriarch des Rudel]]** (**[[Rudel (Löwe)]]**)
- 

## Spezialaktion

- **[[Brüllen]]** (2 AP)
- **[[Gnadenstoß]] (4)** (2 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---