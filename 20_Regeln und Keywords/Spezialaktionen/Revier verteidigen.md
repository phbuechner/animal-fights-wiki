---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Revier verteidigen

**Regel:** Bis zum Beginn seiner nächsten Aktivierung erhält dieses Tier +2
[[Verteidigung]]. Wenn ein gegnerisches Tier in dieser Zeit einen Angriff gegen dieses Tier
deklariert, verliert es sofort 1 Ausdauer.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier", 
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC