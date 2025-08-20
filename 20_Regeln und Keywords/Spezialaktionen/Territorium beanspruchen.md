---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Territorium beanspruchen
**Regel:** Suche eine Arena aus den obersten 3 Karten deines Decks und spiele sie. Wenn du dies tust, erhält dieses Tier sofort einen Ansehen-Marker.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC