---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Drohgebärde
**Regel:** Führe einen [[Einschüchterung-Test]] gegen ein gegnerisches Tier durch. Wenn du erfolgreich bist, darfst du sofort einen kostenlosen Grundangriff gegen dieses Ziel durchführen.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC


