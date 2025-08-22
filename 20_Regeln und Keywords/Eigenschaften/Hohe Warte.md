---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Hohe Warte
**Regel:**  Ein Tier, bei dem "Hohe Warte" aktiv ist, profitiert von folgenden Vorteilen:
- Gegnerische [[Boden]]tiere müssen **1 [[Ausdauer]] zusätzlich** bezahlen, um dieses Tier anzugreifen.
- Angriffe gegen dieses Tier können **nicht von Boni durch die [[Ansturm]]-Fähigkeit profitieren**.


## Tiere mit dieser Fähigkeit  

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````



