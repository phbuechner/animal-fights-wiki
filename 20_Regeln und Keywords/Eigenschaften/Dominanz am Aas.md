---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Dominanz am Aas

**Regel:** Solange dieses Tier im Spiel ist, können gegnerische Tiere keine **[[Aasfresser]]**- und keine **[[Letzter Wille]]**-Fähigkeiten nutzen. 

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
