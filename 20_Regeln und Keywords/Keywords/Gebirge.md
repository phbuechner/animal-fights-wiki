---
typ: "Keyword"
tags:
  - keyword
  - habitat
---

# Gebirge

Das **Gebirge** ist ein [[Habitat-System|Habitat]], das durch steile Hänge, Felsformationen und große Höhenunterschiede gekennzeichnet ist.

---
## Arenen in diesem Habitat

```dataview
TABLE WITHOUT ID
  file.link as "Arena",
  sterne as "★",
  terrain_keywords as "Terrain"
FROM #arenakarte
WHERE contains(habitat, "Gebirge")
SORT sterne DESC
```
## ## Tiere, die in diesem Habitat leben
```dataview
TABLE WITHOUT ID   
  file.link as "Tier",   
  sterne as "★"
FROM #tierkarte 
WHERE contains(habitat, "Gebirge") 
SORT sterne DESC