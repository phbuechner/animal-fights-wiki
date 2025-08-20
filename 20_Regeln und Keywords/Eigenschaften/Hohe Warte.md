---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Hohe Warte
**Regel:** Angreifer müssen +1 Ausdauer zahlen, um dieses Tier anzugreifen (außer [[Fliegend]] oder [[Kletternd]]).
## Tiere mit dieser Fähigkeit  

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````



