---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Instinktives Rufen (Kartentyp)
Ziehe eine Karte. Wenn die gezogene Karte dem angegebenen Kartentyp entspricht, darfst du sie sofort ausspielen. Sie kann in dieser Runde nicht mehr handeln.
## Tiere mit dieser Fähigkeit  

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
