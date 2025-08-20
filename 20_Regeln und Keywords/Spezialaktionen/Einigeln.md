---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Einigeln
**Regel:** Erhalte +2 Verteidigung bis zum Beginn deines nächsten Zuges. Du kannst in deinem nächsten Zug nicht angreifen.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
```
