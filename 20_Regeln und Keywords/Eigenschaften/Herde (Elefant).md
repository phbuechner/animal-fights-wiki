---
typ: "Gruppierung-Spezifisch"
tags:
  - herde
---  
# Herde (Elefant)  
Dies ist eine spezifische Art von [[Herde]]. Nur Tiere mit dieser Eigenschaft können sich einer Elefanten-Herde anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC