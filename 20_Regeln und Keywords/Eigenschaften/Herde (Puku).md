---
typ: "Gruppierung-Spezifisch"
tags:
  - herde
---  
# Herde (Puku) 
Dies ist eine spezifische Art von [[Archetyp - Herde]]. Nur Tiere mit dieser Eigenschaft können sich einer Puku-Herde anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne"  
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC