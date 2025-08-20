---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Resistenz (X)

**Regel:** Dieses Tier kann nicht von Effekten oder Zuständen des Typs X betroffen sein.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````



