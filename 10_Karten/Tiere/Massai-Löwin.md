---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 3
name: Massai-Löwin
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 009"
stärke: 4
verteidigung: 4
gesundheit: 5
agilität: 5
ausdauer: 5
ap: 2
habitat: ["Savanne", "Trockengebiet"]
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

# Massai-Löwin

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |
## Eigenschaften

- **[[Rudel (Löwe)]]**
- **[[Kooperative Jagd]]**
- [[Anpassung (Offenes Gelände)]]
	- Anpassung:: Offenes Gelände
	- Effekt:: Andere Tiere deiner [[Rudel (Löwe)|Gruppierung]] erhalten +1 auf Angriffswürfe gegen ein Ziel, das von dieser Löwin in diesem Zug bereits angegriffen wurde.


## Spezialaktion

- **[[Jagdruf]]** (1 AP)

## Strategische Notizen & Synergien

-
---
%%
- **Keywords**: `=join(map(this.keywords, (k) => "[[" + k + "]]"), " ")`
- **Habitat**: `=join(map(this.habitat, (h) => "[[" + h + "]]"), " ")`
- **Klimazone**: `=join(map(this.klimazone, (c) => "[[" + c + "]]"), " ")`
%%
---