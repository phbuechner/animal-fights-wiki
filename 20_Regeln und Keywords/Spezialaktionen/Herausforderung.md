---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Herausforderung (X)
**Regel:** Führe einen Einschüchterung-Test gegen ein Ziel durch. Dieser Test erhält +X auf den Würfelwurf.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC