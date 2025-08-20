---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Tiefer Tauchgang

**Regel:** Ein Tier mit dieser Eigenschaft profitiert von besonderem Schutz, wenn es
sich in seinem aquatischen Versteck befindet. Wenn dieses Tier die Eigenschaft [[Tarnung]] durch eine Arena mit dem Keyword Wasser oder Sumpf erhält, gilt es zusätzlich als [[Schwimmend]].

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

