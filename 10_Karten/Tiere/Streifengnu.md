---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 2
name: Streifengnu
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 024"
stärke: 3
verteidigung: 4
gesundheit: 4
agilität: 3
ausdauer: 6
ap: 2

# --- STRATEGISCHE IDENTITÄT ---
spielweise: "Gruppe"
archetypen: ["Herde"] 
gruppensubtyp: "Streifengnu" 

habitat: ["Savanne", "Feuchtgebiet"]
heimvorteil_effekt: ""
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



| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Streifengnu)]]
- [[Sicherheit in der Masse]]
	- Anzahl:: 3
	- Effekt:: Erhält [[Wachsamkeit]] und Kann nicht als Ziel von gegnerischen Spezialaktionen gewählt werden.
- [[Stampede]]

## Spezialaktionen
- **[[Weidegrund suchen]]** (2 AP) 
- **[[Verwirrungstaktik]]** (1 AP) 

## Strategische Notizen & Synergien

-
