---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Durchbohrender Sprung
**Regel:** Führe einen Angriff durch. Ignoriert die [[Panzer]]-Fähigkeit des Ziels, wenn deine Basis-Agilität höher ist als die des Ziels.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC


