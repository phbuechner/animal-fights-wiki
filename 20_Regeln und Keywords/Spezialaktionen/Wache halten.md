---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Wache halten
**Regel:** Du kannst in diesem Zug keine weiteren Aktionen mit diesem Tier ausführen. Wähle die anderen Tiere deiner [[Gruppierungseigenschaft|Gruppierung]]. Sie erhalten [[Resistenz]] ([[Gnadenstoß]]) und für die nächste Runde +2 auf ihre Initiative-Würfe

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
