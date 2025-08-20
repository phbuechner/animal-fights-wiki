---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Abschütteln
**Regel:** Entferne einen negativen [[Zustand]] oder einen negativen temporären Effekt von diesem Tier.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
