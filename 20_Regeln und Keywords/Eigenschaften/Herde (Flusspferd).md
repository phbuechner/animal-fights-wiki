---
typ: "Gruppierung-Spezifisch"
tags:
  - herde
---  
# Herde (Flusspferd)
Dies ist eine spezifische Art von [[Archetyp - Herde]]. Nur Tiere mit dieser Eigenschaft können sich einer Flusspferd-Herde anschließen. 

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC