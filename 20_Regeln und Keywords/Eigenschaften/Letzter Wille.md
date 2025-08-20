---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Letzter Wille (X)

**Regel:** Wenn dieses Tier besiegt wird, löse den angegebenen Effekt aus.

## Karten mit dieser Fähigkeit

```dataview 
TABLE WITHOUT ID   
  file.link as "Tier", 
  sterne as "Sterne",
  L.children.Effekt as "Effekt"
FROM #tierkarte
FLATTEN file.lists as L
WHERE contains(L.outlinks, this.file.link) AND L.children
SORT sterne DESC
```



