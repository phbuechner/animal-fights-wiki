---
typ: "Gruppierung-Spezifisch"
tags:
  - rotte
---  
# Rotte (Riesenwaldschwein)
Dies ist eine spezifische Art von [[Rotte]]. Nur Tiere mit dieser Eigenschaft können sich einer Riesenwaldschwein Rotte anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC