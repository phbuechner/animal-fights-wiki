---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Todesrolle
**Regel:** Führe einen Angriff durch. Wenn dieser Angriff Schaden verursacht, erhält das Ziel den Zustand [[Festgehalten]].

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC