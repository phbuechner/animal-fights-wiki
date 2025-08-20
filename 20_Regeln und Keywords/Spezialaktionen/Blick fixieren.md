---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Blick fixieren
**Regel:** Kann nur im [[Lauernd]]-Status genutzt werden. Wähle ein gegnerisches Tier. Es erleidet -2 auf alle Würfe für Ausweichen-Reaktionen bis zum Beginn deines nächsten Zuges. Diese Aktion beendet nicht den Zug deines Tieres.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
