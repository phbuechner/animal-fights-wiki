---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Listiger Vorstoß

**Regel:** Der nächste Angriff dieses Tieres in diesem Zug ignoriert [[Vergeltung]] des Ziels.


## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC