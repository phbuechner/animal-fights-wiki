---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Sichere Position
**Regel:** Erhält bis zum Beginn deines nächsten Zuges [[Resistenz]] (Instinktkarten).

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC