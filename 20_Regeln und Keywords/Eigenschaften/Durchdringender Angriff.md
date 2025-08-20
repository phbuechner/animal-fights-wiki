---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Durchdringender Angriff (Status)

**Regel:** Immer, wenn ein Angriff von einem Tier mit dieser Fähigkeit Schaden verursacht, erhält das Ziel zusätzlich den angegebenen [[Status-Effekte (Übersicht)|Status]].

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
