---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Aasfresser

**Regel:** Immer, wenn ein Tier auf dem Feld besiegt wird, erhält dieses Tier den angegebenen Effekt.

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

