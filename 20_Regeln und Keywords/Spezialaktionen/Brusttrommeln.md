---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Brusttrommeln
**Regel:** Führe einen [[Einschüchterung-Test]] gegen jedes gegnerische Tier durch.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC


