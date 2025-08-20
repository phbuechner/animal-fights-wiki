---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Terrain Erkunden
**Regel:** Decke die obersten 3 Karten des allgemeinen Decks auf. Du darfst eine aufgedeckte [[Arenakarten|Arenakarte]] wählen und sie oben auf das Deck legen. Lege die restlichen Karten in zufälliger Reihenfolge unter den Stapel.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC