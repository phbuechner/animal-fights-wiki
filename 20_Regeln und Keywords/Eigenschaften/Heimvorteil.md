---
typ: "Fähigkeit-Spezifisch"
tags:
  - heimvorteil
---  

# Heimvorteil
**Regel:** Diese Fähigkeit ist aktiv, wenn das Habitat dieses Tieres mit dem der aktiven Arena übereinstimmt. Der spezifische Bonus steht auf der Karte.  
## Tiere mit dieser Fähigkeit  

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