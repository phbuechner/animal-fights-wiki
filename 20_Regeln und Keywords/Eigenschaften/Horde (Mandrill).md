---
typ: "Gruppierung-Spezifisch"
tags:
  - horde
--- 
# Horde (Mandrill)  

Dies ist eine spezifische Art von [[Horde]], die von Mandrills gebildet wird. Sie wird vom [[Mandrill Alphamännchen]] angeführt und zeichnet sich durch starke Einschüchterungs-Effekte und interne Synergien aus.


## Tiere mit dieser Eigenschaft  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC