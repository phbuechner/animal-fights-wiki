---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Architekt des Waldes

**Regel:** Wenn du dieses Tier ausspielst, darfst du dein Deck oder deinen Ablagestapel nach einer Arenakarte mit dem Habitat [[Wald]] durchsuchen, sie deinem Gegner zeigen und oben auf dein Deck legen.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

