---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Panik-Sprung

**Regel:** Wenn dieses Tier als Ziel eines Angriffs gewählt wird, darfst du es sofort auf deine Hand zurücknehmen, bevor der Angriff verrechnet wird. Der Angriff endet ohne Ergebnis.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


