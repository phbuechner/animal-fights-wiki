---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Trampeln (X) 
**Regel:** Eine Spezialaktion, die AP kostet. Wähle bis zu X gegnerische Tiere einer bestimmten Größenkategorie (meistens [[Klein]]). Füge jedem Z direkten Schaden zu. 
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC