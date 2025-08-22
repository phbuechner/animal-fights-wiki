---
typ: Arenakarte
deck_typ: "Persönlich"
sterne: 1
name: Die goldenen Ebenen der Massai Mara
edition: "Savannen Edition, Afrika Saga"
set_nummer: "SEAF 040"
habitat:
  - Savanne
terrain_keywords:
  - Offenes Gelände
  - Dämmerung
klima:
  - Gemäßigt
tags:
  - karte/arenakarte
---

# Die goldenen Ebenen der Massai Mara

| Eigenschaft | Wert |
|---|---|
| **Sterne** | `=this.sterne` |
| **Habitat** | `=[this.habitat]` |
| **Terrain-Keywords** | `=this.terrain_keywords` |
| **Klima** | `=[this.klima]` |

## Regeltext & Effekte

> *[[Dämmerungsaktiv]]e Tiere erhalten [[Heimvorteil]]: +1 Agilität. 
> Immer wenn eine deiner [[Fleischfresser-Gruppierungen]] (3★+) einen Angriff deklariert, ziehe 1 Karte.*

---
## Strategische Überlegungen



---

## Tiere mit Heimvorteil

Die folgende Tabelle listet automatisch alle Tiere aus Ihrem Vault auf, deren Primär-Habitat mit dem dieser Arena übereinstimmt. Diese Tiere erhalten hier ihren "Heimvorteil"-Bonus.

```dataview 
TABLE
  sterne as "Sterne",
  heimvorteil_effekt as "Heimvorteil Effekt"
FROM #tierkarte
WHERE heimvorteil_effekt AND contains(habitat, "Savanne")
SORT sterne DESC
```

## Tiere mit Anpassungs-Vorteil

Die folgende Tabelle listet automatisch alle Tiere auf, die eine "Anpassung"-Fähigkeit besitzen, die zu einem der Terrain-Keywords dieser Arena passt.

```dataview
TABLE anpassungen as "Angepasst an"
FROM #tierkarte
WHERE anpassungen AND any(anpassungen, (p) => contains(["Offenes Gelände", "Dämmerung"], p))
SORT file.name ASC
```
# Notizen
- Druckfehler