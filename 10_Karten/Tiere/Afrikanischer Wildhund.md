---
typ: Tierkarte
deck_typ: Persönlich
sterne: 2
name: Afrikanischer Wildhund
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 014
stärke: 3
verteidigung: 2
gesundheit: 3
agilität: 5
ausdauer: 5
ap: 2

# --- STRATEGISCHE IDENTITÄT ---
spielweise: "Gruppe"
archetypen: ["Rudel"] 
gruppensubtyp: "Afrikanischer Wildhund" 

habitat:
  - Savanne
  - Trockengebiet
anpassungen:
  - Offenes Gelände
klimazone:
  - Arid
keywords:
  - Mittel
  - Fleischfresser
  - Boden
  - Tagaktiv
tags:
  - tierkarte
  - 2-Sterne
---

# Afrikanischer Wildhund

| Attribut      | Wert                                                                                                                    |
| ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Sterne**    | `=this.sterne`                                                                                                          |
| **Werte**     | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat**   | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")`                                                                |
| **Klimazone** | `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")`                                                              |
| **Keywords**  | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")`                                                               |
## Eigenschaften

- **[[Rudel (Afrikanischer Wildhund)]]**
- **[[Kooperative Jagd]]**

## Spezialaktion

- **[[Versammeln]]** (2 AP)

## Strategische Notizen & Synergien

-
---
%%
Keywords: [[Mittel]], [[Fleischfresser]], [[Boden]], [[Tagaktiv]]
Habitat: [[Trockengebiet]], [[Savanne]]
Klimazone: [[Arid]]
%%