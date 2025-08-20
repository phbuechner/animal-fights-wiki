---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Ausspähen
**Regel:** Schaue dir die oberste Karte eines beliebigen Decks an. Du darfst sie unter das Deck legen.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
