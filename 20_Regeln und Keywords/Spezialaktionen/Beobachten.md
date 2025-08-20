---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Beobachten
**Regel:** Wähle einen Gegner. Er deckt die oberste Karte seines Decks auf. Du kannst diese
Karte unter sein Deck legen lassen. Ziehe eine Karte.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
