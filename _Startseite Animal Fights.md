> [!NOTE] Willkommen im ANIMAL FIGHTS Hauptquartier
> Dies ist deine zentrale Anlaufstelle für alles rund um das Spiel. Nutze die folgenden Links, um schnell zu den wichtigsten Bereichen zu navigieren.

---
### **Schnellzugriff & Spielhilfen**
|                                                                                                  |                                                                                                        |
| :----------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------- |
| > [!INFO]- Das Regelwerk<br>- **[[Regel-Glossar]]**<br>- **[[Spielablauf (Kurzreferenz)]]**      | > [!SUCCESS]- Deine Sammlung<br>- **[[Übersicht aller Sagas]]**<br>- **[[Übersicht aller Editionen]]** |
| > [!DANGER]- Strategie & Deckbau<br>- **[[Archetypen (Übersicht)]]**<br>- **[[Deckbau-Regeln]]** | > [!WARNING]- Wichtige Konzepte<br>- **[[Status-Effekte (Übersicht)]]**<br>- **[[Größenkategorien]]**  |

---
### **Sagas & Editionen im Überblick**

Hier siehst du alle bisher erstellten Sagas und Editionen.

```dataview
TABLE WITHOUT ID
  saga as "Saga",
  file.link as "Edition / Erweiterung",
  beschreibung as "Fokus"
FROM #edition OR #saga
SORT saga ASC, typ DESC
```

### **Zuletzt bearbeitete Tiere & Karten**

```dataview
TABLE
  typ as "Typ",
  sterne as "Sterne"
FROM #tierkarte OR #arenakarte OR #instinktkarte
SORT file.mtime DESC
LIMIT 15
```

### **Zufällige Karte entdecken**

Lust auf Inspiration? Hier ist eine zufällige Tierkarte aus deiner Sammlung.

```dataview
TABLE WITHOUT ID
  file.link as "Zufälliges Tier",
  sterne as "★"
FROM #tierkarte
SORT file.name ASC
WHERE dateformat(file.ctime, "ss") = dateformat(date(now), "ss")
LIMIT 3
```
