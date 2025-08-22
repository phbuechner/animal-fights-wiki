---
typ: "Gruppierung-Spezifisch"
tags:
  - herde
---  
# Herde (Kob)  
Dies ist eine spezifische Art von [[Archetyp - Herde]]. Nur Tiere mit dieser Eigenschaft können sich einer Kob-Herde anschließen.  

## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC