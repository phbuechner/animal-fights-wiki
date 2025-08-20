---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Beute sichern
**Regel:** Wähle ein Tier, das du in diesem Zug besiegt hast. Lege es unter diese Karte, anstatt auf deinen Trophäenstapel. Du kannst jederzeit 1 Ausdauer bezahlen, um ein Tier unter dieser Karte aus dem Spiel zu entfernen und 2 Gesundheit zu heilen.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
