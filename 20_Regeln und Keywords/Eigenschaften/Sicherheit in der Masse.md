---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Sicherheit in der Masse (X, Effekt/Eigenschaften) 

**Regel:** Wenn du eine bestimmte Anzahl (X) von Tieren derselben Gruppierung kontrollierst, erhält dieses Tier folgende Effekte/Eigenschaften.

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


