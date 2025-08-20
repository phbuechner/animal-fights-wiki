---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Horst beziehen
**Regel:** Versetze dieses Tier in den [[Lauernd]]-Status. Du darfst danach die obersten 2 Karten des allgemeinen Decks ansehen und eine davon unter das Deck legen.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC