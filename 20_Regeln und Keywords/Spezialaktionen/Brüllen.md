---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Brüllen
**Regel:** Alle gegnerischen Tiere verlieren 1 AP. Wenn du dich im **[[Heimvorteil]]** befindest, verlieren sie stattdessen 2 AP. Regeneriere 1 Gesundheit.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
