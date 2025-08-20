---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Vom Gejagten zum Jäger

**Regel:** Versetze dieses Tier in den [[Lauernd]]-Status. Wenn du dies tust, während dieses Tier die Eigenschaft [[Tarnung]] besitzt, ziehe eine Karte.
## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
