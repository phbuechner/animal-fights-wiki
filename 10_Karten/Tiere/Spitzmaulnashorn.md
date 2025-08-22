---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 4
name: Spitzmaulnashorn
edition: Savannen Edition, Afrika Saga
set_nummer: SEAF 003
erweiterung: ""
stärke: 5
verteidigung: 7
gesundheit: 9
agilität: 2
ausdauer: 8
ap: 3

# --- STRATEGISCHE IDENTITÄT ---
spielweise: "Einzelgänger"
archetypen: ["Einzelgänger"] 
gruppensubtyp: "" 

habitat: ["Trockengebiet", "Savanne"]
heimvorteil_effekt: ""
anpassungen: ["Engpass"]
klimazone: ["Arid"]
keywords:
  - Gigantisch
  - Pflanzenfresser
  - Boden
  - Dämmerungsaktiv
tags:
  - tierkarte
---

# Spitzmaulnashorn

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Einzelgänger (Fähigkeit)|Einzelgänger]]
- [[Ansturm]] (2)
	- Ansturm:: 2
- [[Panzer]] (2)
	- Panzer:: 2

## Spezialaktion

- [[Überrennen]] (2 AP)

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