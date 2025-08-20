---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Loyaler Leibwächter

**Regel:** Reaktion: Einmal pro Runde, wenn ein anderes Tier deiner Gruppe als Ziel eines Angriffs gewählt wird, kannst du stattdessen dieses Tier zum Ziel des Angriffs machen.

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



