---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Amphibisch

**Regel:** Ein Tier mit dieser Eigenschaft erhält in Arenen mit den [[Terrain-Keyword]]s [[Wasser (Keyword)|Wasser]], [[Sumpf (Keyword)|Sumpf]], [[Flussufer (Keyword)|Flussufer]] oder [[Fluss (Keyword)|Fluss]] die folgenden Effekte:

Es ist immun gegen alle negativen Effekte, die von der Arena selbst ausgehen.

Sein [[Heimvorteil]] ist immer aktiv, unabhängig vom Primär-Habitat der Arena.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
  file.link as "Tier",   
  sterne as "Sterne"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

