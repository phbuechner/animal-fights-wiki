---
typ: Spezialaktion
tags:
  - fähigkeit
  - spezialaktion
---

# Gift anreichern
**Regel:** Bis zum Beginn deines nächsten Zuges wird die [[Vergeltung]] ([[Vergiftet]] 1)- Fähigkeit dieses Tieres zu [[Vergeltung]] ([[Vergiftet]] 2).

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
```
