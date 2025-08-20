---
typ: "Gruppierung-Spezifisch"
tags:
  - gemeinschaft
---  
# Gemeinschaft Schimpanse
Dies ist eine spezifische Art von [[Gemeinschaft]]. Nur Tiere mit dieser Eigenschaft können sich einer Schimpansen-Gemeinschaft anschließen. 

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC