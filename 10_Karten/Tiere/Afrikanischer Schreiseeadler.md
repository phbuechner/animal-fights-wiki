---
typ: Tierkarte
deck_typ: ""
sterne: 3
name: Afrikanischer Schreiseeadler
edition: Regenwälder & Flussdeltas
set_nummer: RFAF 005
erweiterung: ""
stärke: 4
verteidigung: 3
gesundheit: 4
agilität: 6
ausdauer: 5
ap: 2
habitat:
  - Feuchtgebiet
heimvorteil_effekt: Du darfst dir jederzeit die oberste Karte des allgemeinen Stapels ansehen.
anpassungen:
  - Wasser
klimazone:
  - Tropisch
keywords:
  - Mittel
  - Fleischfresser
  - Fliegend
  - Tagaktiv
tags:
  - tierkarte
---

# Afrikanischer Schreiseeadler

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Lauerjäger]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Angriffe dieses Tieres können nicht ausgewichen werden.
- [[Heimvorteil]]
	- Effekt:: Du darfst dir jederzeit die oberste Karte des allgemeinen Stapels ansehen.


## Spezialaktion

- **[[Sturzflug]]** (1 AP)
- **[[Weit hallender Schrei]]** (1 AP)
	- Effekt:: [[Spähen]]

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