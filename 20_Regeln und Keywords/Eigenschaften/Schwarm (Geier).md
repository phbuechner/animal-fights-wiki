---
typ: "Gruppierung-Spezifisch"
tags:
  - schwarm
---

# Schwarm (Geier)

Dies ist eine spezifische Art von [[Schwarm]]. Nur Tiere mit dieser Eigenschaft können sich einem Geier-Schwarm anschließen.  

## Spezifische Herden-Arten

```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC