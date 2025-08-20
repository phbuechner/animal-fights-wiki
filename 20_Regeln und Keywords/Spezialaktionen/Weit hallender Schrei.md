---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Weit hallender Schrei 
**Regel:** Wende [[Spähen]] (3, Fliegend) auf dein Deck an ODER wende [[Spähen]] (3, Arena) auf das allgemeine Deck an.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
