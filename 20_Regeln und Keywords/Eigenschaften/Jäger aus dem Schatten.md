---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Jäger aus dem Schatten

**Regel:** Wenn dieses Tier aus dem [[Lauernd]]-Status angreift, erhält der Angriff [[Durchbruch]].

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


