---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Lauert im Schatten

**Regel:** Solange dieses Tier im [[Lauernd]]-Status ist, kann es nicht als Ziel von
[[Spezialaktionen]] oder [[Instinktkarten]] gewählt werden.

## Karten mit dieser Fähigkeit

```dataview 
TABLE WITHOUT ID   
  file.link as "Tier", 
  sterne as "Sterne"
FROM #tierkarte
FLATTEN file.lists as L
WHERE contains(L.outlinks, this.file.link)
SORT sterne DESC
```



