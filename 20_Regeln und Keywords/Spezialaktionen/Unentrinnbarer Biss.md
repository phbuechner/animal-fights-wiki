---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Unentrinnbarer Biss
**Regel:** Dein nächster Angriff in diesem Zug kann nicht [[Ausweichen|ausgewichen]] werden.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
