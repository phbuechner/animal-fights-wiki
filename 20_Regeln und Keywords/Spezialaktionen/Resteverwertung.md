---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Resteverwertung
**Regel:** Wähle eine Karte aus einem beliebigen Ablagestapel und mische sie in das Allgemeine-Deck. Ziehe danach eine Karte.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier", 
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC