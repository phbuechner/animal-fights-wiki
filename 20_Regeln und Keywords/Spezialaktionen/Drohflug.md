---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Drohflug

**Regel:** Wähle ein gegnerisches Tier. Es erhält -2 auf seinen Initiative-Wurf in der nächsten Runde.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier", 
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC


