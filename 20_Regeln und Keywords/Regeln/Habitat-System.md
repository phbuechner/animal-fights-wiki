---
typ: "Spielkonzept"
tags:
  - regelwerk
---

# Habitat-System

Das Habitat-System ist ein entscheidender strategischer Faktor, der die Interaktion zwischen Tieren und der aktiven Arena regelt. Es besteht aus drei Komponenten.

### 1. Habitat
- Jedes Tier und jede Arena hat ein oder mehrere Primär-Habitate (z.B. [[Savanne]], [[Wald]], [[Feuchtgebiet]]).
- Dies definiert die grundlegende Umgebung.
Klicken Sie auf ein Habitat, um eine detaillierte Liste der zugehörigen Arenen und Tiere zu sehen.

```dataview
LIST
FROM #habitat
SORT file.name ASC
```
### 2. Terrain-Keywords
- Jede Arena besitzt zusätzlich eine Liste von [[Terrain-Keyword|Terrain-Keywords]], die das Schlachtfeld genauer beschreiben (z.B. [[Unterholz (Keyword)|Unterholz]], [[Wasser (Keyword)|Wasser]], [[Felsen (Keyword)|Felsen]]).

### 3. Fähigkeiten, die das Habitat nutzen

#### A) [[Heimvorteil]]
- **Bedingung:** Das Primär-Habitat des Tieres stimmt mit dem Primär-Habitat der Arena überein.
- **Effekt:** Das Tier erhält den spezifischen Bonus, der auf seiner Karte beschrieben ist.
- **Beispiel:** Ein [[Massai-Löwe]] (Habitat: Savanne) in der Arena [[Die goldenen Ebenen der Massai Mara]] (Habitat: Savanne).

#### B) [[Anpassung]]
- **Bedingung:** Die Arena besitzt ein Terrain-Keyword, an das das Tier angepasst ist.
- **Effekt:** Das Tier erhält den spezifischen Bonus, unabhängig vom Primär-Habitat.
- **Beispiel:** Ein [[Tsavo-Löwe]] (Anpassung an Unterholz) in der Arena [[Dornenbusch-Dickicht]] (Terrain-Keyword: Unterholz).
