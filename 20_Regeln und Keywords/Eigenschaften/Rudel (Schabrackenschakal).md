---
typ: "Gruppierung-Spezifisch"
tags:
  - rudel
---  
# Rudel (Schabrackenschakal)  
Dies ist eine spezifische Art von [[Rudel]]. Nur Tiere mit dieser Eigenschaft können sich einem Schabrackenschakal Rudel anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC