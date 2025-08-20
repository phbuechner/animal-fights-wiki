---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Spähen (X, Kartentyp)
**Regel:** Führe einen Angriff durch. Für diesen Angriff entspricht die Stärke dieses Tieres seiner Agilität. Nachdem der Kampf verrechnet wurde, erleidet dieses Tier den Zustand [[Erschöpft]].

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC