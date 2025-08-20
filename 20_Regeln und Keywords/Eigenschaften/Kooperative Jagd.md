---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Kooperative Jagd

**Regel:** Ein Angriff dieses Tieres kann nicht ausgewichen werden, wenn das Ziel in dieser Runde bereits von einem anderen Mitglied derselben Gruppierung angegriffen wurde.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


