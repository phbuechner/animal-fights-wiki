---
typ: "Gruppierung-Spezifisch"
tags:
  - herde
---  
# Herde (Gazelle)  
Dies ist eine spezifische Art von [[Herde]]. Nur Tiere mit dieser Eigenschaft können sich einer Gazellen-Herde anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC