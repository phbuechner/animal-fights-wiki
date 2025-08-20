---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Schattenflucht

**Regel:** Führe einen Angriff durch. Wenn dieser Angriff Schaden verursacht, versetze dieses Tier sofort in den [[Lauernd]]-Status.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC