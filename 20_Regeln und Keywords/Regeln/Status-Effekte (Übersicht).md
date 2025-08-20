---
typ: "Übersicht"
tags:
  - regelwerk
---

# Status-Effekte (Übersicht)

Status-Effekte sind besondere Zustände, die die Regeln für ein Tier verändern. Sie werden in positive und negative Zustände unterteilt.

---
## Alle definierten Status-Effekte

Die folgende Liste wird automatisch aktualisiert, sobald Sie eine neue Notiz für einen Status-Effekt erstellen.

### Positive Zustände
```dataview
LIST
FROM #status-effekt AND #positiv
```

### Negative Zustände
 
 ```dataview
LIST
FROM #status-effekt AND #negativ
```

### Karten die Statusveränderungen verursachen

 ```dataview
 TABLE WITHOUT ID
  file.link as "Verursachende Karte"
FROM #tierkarte OR #instinktkarte OR #arenakarte
FLATTEN file.lists as L
WHERE length(filter(L.outlinks, (link) => link.file.tags AND contains(link.file.tags, "status-effekt"))) > 0
SORT file.name ASC
```