---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Sicherheit in der Masse (X)

**Regel:** Ein Keyword, das dieses Tier schützt, wenn du eine bestimmte Anzahl (X) von Tieren derselben Gruppierung kontrollierst. Der spezifische Bonus steht auf der Karte.

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


