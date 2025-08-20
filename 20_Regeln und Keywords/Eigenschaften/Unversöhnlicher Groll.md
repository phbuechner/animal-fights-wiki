---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Unversöhnlicher Groll

**Regel:** Markiert Tiere, die einem deiner Tiere Schaden zufügen. Alle deine Tiere erhalten +1 Verteidigung gegen markierte Ziele.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

