---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Versammeln
**Regel:** Durchsuche dein Deck nach einer Karte mit demselben Namen wie dieses Tier und bringe sie sofort ins Spiel. Mische danach dein Deck.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
