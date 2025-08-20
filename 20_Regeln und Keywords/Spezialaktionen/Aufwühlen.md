---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Aufwühlen
**Regel:** Wähle ein [[Terrain-Keyword]] der aktiven Arena. Dieses Keyword ist bis zum Beginn deines nächsten Zuges deaktiviert.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
