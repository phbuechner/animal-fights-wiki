---
typ: "Gruppierung-Spezifisch"
tags:
  - rotte
---  
# Rotte (Pinselohrschwein)
Dies ist eine spezifische Art von [[Rotte]]. Nur Tiere mit dieser Eigenschaft können sich einer Pinselohrschwein Rotte anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC