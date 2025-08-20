---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Sprungangriff 
**Regel:** Führe einen Angriff gegen ein Ziel mit dem Bewegungstyp [[Fliegend]] durch. Dieser Angriff erhält +2 Stärke.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC