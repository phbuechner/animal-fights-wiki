---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Hetzjagd
**Regel:** Wähle ein gegnerisches Tier. Es verliert sofort 1 Ausdauer.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier", 
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC