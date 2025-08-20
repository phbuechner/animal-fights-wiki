---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Verteidigungshaltung (X) 
**Regel:** Erhalte +X Verteidigung bis zum Beginn deines nächsten Zuges.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
