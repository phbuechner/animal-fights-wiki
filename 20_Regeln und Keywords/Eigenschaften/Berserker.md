---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Berserker

**Regel:** Nachdem dieses Tier durch einen Angriff Schaden erlitten hat, ist sein nächster Angriff in dieser Runde kostenlos (kostet 0 AP statt 1 AP).

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

