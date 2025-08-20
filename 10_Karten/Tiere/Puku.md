---
typ: Tierkarte
deck_typ: "Persönlich"
sterne: 1
name: Puku
edition: Savannen Edition, Afrika Saga
set_nummer: "SEAF 035"
erweiterung: ""
stärke: 1
verteidigung: 2
gesundheit: 3
agilität: 5
ausdauer: 4
ap: 2
habitat: ["Feuchtgebiet", "Savanne"]
heimvorteil_effekt: "Kann nicht von Tieren im Lauernd-Status angegriffen werden."
anpassungen: ["Wasser"]
klimazone: ["Tropisch"]
keywords: ["Mittel", "Pflanzenfresser", "Boden", "Schwimmend", "Tagaktiv"]
tags:
  - tierkarte
---

# Puku

| Attribut | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Werte** | S `=this.stärke`, V `=this.verteidigung`, G `=this.gesundheit`, A `=this.agilität`, Aus `=this.ausdauer`, AP `=this.ap` |
| **Habitat** | `=join(map(this.habitat, (h) => "[[" + h + "]]"), ", ")` |
| **Klimazone**| `=join(map(this.klimazone, (k) => "[[" + k + "]]"), ", ")` |
| **Keywords** | `=join(map(this.keywords, (k) => "[[" + k + "]]"), ", ")` |

## Eigenschaften

- [[Herde (Puku)]]
- [[Anpassung (Wasser)]]
	- Anpassung:: Wasser
	- Effekt:: Einmal pro Runde, wenn angegriffen, kannst du dieses Tier auf deine Hand zurücklegen. Der Angreifer verliert 1 Ausdauer.
- [[Heimvorteil]]
	- Effekt:: Kann nicht von Tieren im [[Lauernd]]-Status angegriffen werden.

## Spezialaktion

- 

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