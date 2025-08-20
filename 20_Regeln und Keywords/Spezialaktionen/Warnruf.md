---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Warnruf 
**Regel:** Wähle ein anderes Tier deiner [[Gruppierungseigenschaft|Gruppierung]]. Bis zum Beginn deines nächsten Zuges erhält es **+2 Agilität**.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
