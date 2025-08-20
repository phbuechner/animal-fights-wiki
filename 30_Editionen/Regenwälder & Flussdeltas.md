---
typ: "Edition"
saga: "[[Afrika Saga]]"
beschreibung: "Die zweite Edition der Afrika Saga, die die Wasser- und Wald-Thematik als zentrales Element einführt."
tags:
  - edition
---

# Regenwälder & Flussdeltas

**Regenwälder & Flussdeltas** ist die zweite Edition in der **[[Afrika Saga]]**. Sie verlagert den Fokus von den offenen Ebenen in die dichten, nassen und gefährlichen Lebensräume der afrikanischen Flussdeltas und Regenwälder.

Das Set führt nicht nur neue, mächtige Tiere ein, sondern vertieft auch bestehende Archetypen und etabliert mit **[[Amphibisch]]**, **[[Vergiftet|Gift]]** und erweiterter **[[Tarnung]]** komplett neue strategische Pfade.

---
## Thematischer Fokus & Design-Ziele

Gemäß der Roadmap verfolgt diese Edition folgende Ziele:

- **Einführung der Wasser- und Wald-Thematik:** Das Spiel wird um eine vertikale (Baumkronen) und eine aquatische (Wasser) Ebene erweitert.
- **Neue Kern-Mechaniken:** Etablierung von [[Amphibisch]] als neuem Keyword und Vertiefung der [[Vergiftet|Gift]]- und [[Tarnung]]-Mechaniken.
- **Vertiefung bestehender Archetypen:** [[Fliegend]], [[Lauerjäger]] und [[Gemeinschaft]]s-Gruppierungen werden durch neue Karten vervollständigt und erhalten mehr strategische Tiefe.

---
## Die Regionen & ihre Bewohner

Die Welt dieser Edition ist in sechs thematische Regionen unterteilt, die jeweils unterschiedliche Habitate und strategische Schwerpunkte repräsentieren.

### Flussdeltas
1.  **[[Okavangodelta (Region)|Okavangodelta]]** 
    - Ein Labyrinth aus Kanälen und Sümpfen. Ikonische Tiere sind der [[Afrikanischer Schreiseeadler]], der [[Schuhschnabel]] und die Sumpfantilope [[Letschwe]].
2.  **[[Nigerdelta (Region)|Nigerdelta]]** 
    - Dichte Mangrovenwälder und Brackwasser. Dominiert vom [[Flusspferd Bulle]] und dem [[Schimpanse (Werkzeugmeister)|Schimpansen (Nigerdelta)]].
3.  **[[Sambesidelta (Region)|Sambesidelta]]** 
    - Breite Flussläufe und die Mündung ins Meer. Heimat von riesigen [[Nilkrokodil]]en und [[Afrikanischer Waldelefant]]-Herden.

### Regenwälder
4.  **[[Kongobecken (Region)|Kongobecken]]**
    - Das riesige, unergründliche Herz der afrikanischen Regenwälder. Heimat des [[Berggorilla Silberrücken]], des [[Kongo Leopard]]en und der tödlichen [[Schwarze Mamba]].
5.  **[[Regenwälder Kameruns (Region)|Regenwälder Kameruns]]** 
    - Artenreiche Wälder an Vulkanhängen. Hier jagt der mächtige [[Kronenadler]] und der farbenfrohe [[Mandrill]].
6.  **[[Östliche-Arc-Gebirge (Region)|Östliche-Arc-Gebirge]]**
    - Uralte Gebirgswälder mit einzigartigen Arten wie der [[Grüne Mamba]] und dem [[Senegal-Schirrantilope]].

---
## Zukünftige Mini-Erweiterungen

Diese Edition legt den Grundstein für zukünftige, thematisch passende Mini-Erweiterungen wie:
- **[[Nächtliche Jäger]]**: Vertieft die Nachtaktiv- und Tarnung-Mechaniken.
- **[[Gesetz des Flusses]]**: Stärkt den Amphibisch-Archetyp.
- **[[Symphonie der Baumkronen]]**: Fokus auf Fliegend- und Kletternd-Mechaniken.

---
## Vollständige Kartenliste

```dataview
TABLE WITHOUT ID
  set_nummer as "Nr.",
  file.link as "Karte",
  erweiterung as "Erweiterung",
  sterne as "★",
  typ as "Typ"
FROM #tierkarte OR #arenakarte OR #instinktkarte
WHERE edition = "Regenwälder & Flussdeltas"
SORT set_nummer ASC