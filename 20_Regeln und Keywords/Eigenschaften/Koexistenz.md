---
typ: "Fähigkeit"
tags:
  - keyword
  - fähigkeit
---

# Koexistenz

**Koexistenz** ist eine seltene und mächtige passive Fähigkeit, die eine der fundamentalsten Regeln des Spiels bricht: die "Ein-Tier/Eine-Gruppe"-Regel.

## Regeltext & Effekt

Normalerweise darf ein Spieler nur **ein einzelnes Tier** ODER **eine einzelne Gruppe** (z.B. ein [[Rudel]] oder eine [[Archetyp - Herde]]) gleichzeitig im Spiel haben.

Die Fähigkeit "Koexistenz" erlaubt es einem Tier, **zusätzlich** zu einem bereits vorhandenen Einzelgänger oder einer Gruppe im Spiel zu sein.

**Beispiel:**
Ein Spieler kontrolliert einen [[Afrikanischer Elefant]] (ein [[Einzelgänger (Fähigkeit)]]). Normalerweise dürfte er kein weiteres Tier spielen. Wenn er jedoch ein Tier mit "Koexistenz" auf der Hand hat (z.B. den [[Marabu]]), darf er dieses **zusätzlich** spielen. Er kontrolliert dann den Elefanten UND den Marabu.

---
## Tiere mit der Fähigkeit "Koexistenz"

Die folgende Tabelle listet automatisch alle Tiere auf, die die Fähigkeit "Koexistenz" besitzen.

```dataview
TABLE WITHOUT ID   
  file.link as "Tier",    
  sterne as "★",
  stärke as "S",
  verteidigung as "V",
  agilität as "A"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
SORT sterne DESC
````