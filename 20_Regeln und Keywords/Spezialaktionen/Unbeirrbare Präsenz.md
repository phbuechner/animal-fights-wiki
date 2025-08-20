---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Unbeirrbare Präsenz
**Regel:** Wenn du deinen Zug beendest und mit diesem Tier nicht angegriffen oder eine Spezialaktion genutzt hast, muss dein Gegner 1 Karte abwerfen.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
