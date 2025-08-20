---
typ: "Saga"
tags:
  - saga
---

# Afrika Saga

Die **Afrika Saga** ist der erste große Zyklus von *Animal Fights* und entführt die Spieler auf den afrikanischen Kontinent.

---
## Editionen in dieser Saga

```dataview
TABLE WITHOUT ID
  file.link as "Edition",
  beschreibung as "Beschreibung"
FROM #edition
WHERE saga = this.file.link AND typ = "Edition"
SORT file.name ASC
````
---
## Mini-Erweiterungen in dieser Saga

```dataview
TABLE WITHOUT ID
  file.link as "Mini-Erweiterung",
  gehört_zu as "Gehört zu"
FROM #edition
WHERE saga = this.file.link AND typ = "Mini-Erweiterung"
SORT gehört_zu ASC
````