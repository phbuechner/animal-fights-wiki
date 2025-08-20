---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Wachsamkeit gewähren
**Regel:** Wähle eines deiner Tiere (kann dieses sein). Bis zum Beginn deines nächsten Zuges kann das gewählte Tier nicht von Tieren im [[Lauernd]]-Status angegriffen werden.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier", 
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
