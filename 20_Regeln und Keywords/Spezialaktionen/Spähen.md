---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Spähen (X, Kartentyp)
**Regel:** Schaue dir die obersten X Karten deines Decks an. Du darfst eine Karte des Typs [Kartentyp] davon auf deine Hand nehmen. Mische den Rest zurück ins Deck.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC