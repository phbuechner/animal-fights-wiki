---
typ: Spezialaktion
tags:
  - fähigkeit
  - spezialaktion
---

# Gnadenstoß (X)
**Regel:** Führe einen Angriff durch. Wenn das Ziel 50% oder weniger seiner maximalen Gesundheit hat, erhält dieser Angriff +X Stärke.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
```
