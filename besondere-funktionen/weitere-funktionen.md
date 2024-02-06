---
label: Weitere Funktionen
layout: default
order: 394
icon: plus-circle
---

# Weitere Funktionen

Auf dieser Seite sind weitere, kleinere Themen vertreten.

---

## Sign-Editor
Mit dem Sign-Editor kannst du Schilder kopieren und editieren.

### Verwendung
Nutze `/sign`, um den Modus ein- und auszuschalten.

Schlägst du ein Schild mit einem Schild in deinem Inventar, wird dessen Inhalt kopiert und du kannst ein neues Schild mit dem kopierten Inhalt platzieren. Wenn du den Modus wieder ausschaltest, kannst du das Schild wieder ohne kopierten Inhalt setzen.

Wenn du eine Zeile des kopierten Schildes ändern möchtest, kannst du `/sign <Zeile> <Inhalt>` nutzen. Die Zeilenzahlen beginnen mit `1`, also mit `/sign <1> <Inhalt>` wird die oberste Zeile des Schildes editiert. 

### Gut zu wissen
Die Colorcodes werden von `/sign` nicht zu den maximalen Zeichen gezählt. Ein Schild hat maximal 15 Zeichen Platz pro Zeile. Dennoch ist es möglich, die 15 Zeichen zu überschreiten, wenn man Colorcodes verwendet. 

Auf einem normalen Schild würde der folgende Satz nicht funktionieren: “&5Test&4Test&3Test”, da er 18 Zeichen lang ist. Mit `/sign 1 &5Test&4Test&3Test` funktioniert es trotzdem, da die Colourcodes “&5”, “&4”, “&3” nicht zu den Zeichen gezählt werden. Das Schild hat danach 12 Zeichen in drei Farben.

Außerdem ist eine Kompatibilität zwischen `/sign` und Pipe-Schildern gegeben. Bei größeren Lagern ist ein Zurückgreifen auf diese Funktion also zu empfehlen.

---

## Colorcodes
[!badge variant="dark" icon="ruby" text="VIP/VIS Feature"](/allgemeines/ränge.md)

-![](/images/color_codes.png)
Colorcodes ermöglichen es, bunte Nachrichten im Chat und auf Schildern zu schreiben.

Auf dem Bild findest du eine Auflistung aller möglichen Colorcodes. Es gibt neben den Colorcodes noch einige Formatierungs-Codes, die farb-unabhängige Attribute verändern. Du kannst diese Auflistung ebenfalls ingame mit `/colorcodes` einsehen.

Möchtest du beispielsweise die Nachricht “Hallo” in dunkelblau schreiben, schreibe “&1Hallo” in den Chat. Der Colorcode “&1” verschwindet dann automatisch und färbt jegliche Schrift nach diesem dunkelblau. Um wieder auf die normale Schriftfarbe (weiß) zu wechseln verwende “&f” oder “&r”. “&f” wechselt die Farbe zurück auf weiß, jedoch bleibt andere Formatierung (wie “&l” für fett-gedruckt) erhalten. “&r” setzt jegliche Formatierung und Farbe zurück.

---

## XP-Bottles
Du kannst deine Erfahrungspunkte jederzeit in allen Welten in Flaschen abfüllen. Da sie zu normalen XP-Flaschen werden, kannst du sie zudem in ChestShops verkaufen.

### Befehle
`/bottle stats`\
Zeigt dein aktuelles XP-Level und die benötigten XP bis zum nächsten Level an.

`/bottle get <anzahl/max>`\
Füllt deine vorhandenen XP in die gewünschte/maximale Flaschenmenge ab.

`/bottle store <anzahl/max>`\
Füllt die angegebene Anzahl an XP in eine einzelne Flasche. Diese Flasche kann mit Rechtsklick wieder in Erfahrungspunkte konvertiert werden. Achtung: Die Flasche wird dabei geworfen!

---

## MapArts schützen


---

## Bedrock-Glättung
Es ist möglich, Bedrock in der Bauwelt für Ingamegeld glätten zu lassen. Der Bedrock wird dabei auf die letzte Ebene reduziert.

Der Service kann für 25$ pro Block von einem Admin ausgeführt werden.

Die Anzahl an Blöcken wird in diesem Kontext als die Ausdehnung in x-z-Richtung interpretiert. Für eine horizontale Fläche von 10*10 Blöcken wird daher der Preis für 100 Blöcke verrechnet, auch wenn mehr als 100 Bedrock-Blöcke entfernt werden.

Im Bauwelt-Nether ist eine Entfernung ebenfalls möglich. Das geplante Bauwerk muss dies jedoch zwingend erforderlich machen.

Eine Anfrage für eine Bedrock-Glättung kann mit den Koordinaten der zu glättenden Fläche per Ticket im [!badge variant="primary" target="blank" icon= "comment-discussion" text="Discord"](https://discord.com/invite/ecqPF34) gestellt werden.

---

## Fehlende Advancements freischalten
Aufgrund des Multi-Server-Setups von OpenMC befinden sich die Farmwelt und Industriewelt auf separaten Servern. Da es in der Bauwelt kein End gibt, ist es nicht möglich, bestimmte Advancements auf natürlichem Weg zu erhalten. Die fehlenden Advancements können für einen Geldbetrag dennoch freigeschaltet werden, um die eigene Sammlung zu vervollständigen.

!!!warning Wichtiger Hinweis:
Das Menü prüft nicht, ob du ein Advancement bereits besitzt. Prüfe deshalb bitte vor dem Kauf, ob dies der Fall ist, da Mehrfachkäufe nicht verhindert oder erstattet werden können.
!!!

Nutze `/advancements`, um das Menü für die Freischaltung zu öffnen. Dort kannst du anschließend das gewünschte Advancement auswählen.

### Freischaltbare Advancements
+++ Minecraft
- “The End?” (100k$)
+++ The End
- Free the End (150k$)
- Remote Gateway (100k$)
- The End… Again… (300k$)
- The City at the End of the Game (100k$)
+++ Adventure
- Monsters Hunted (300k$)
- Two Birds, One Arrow (200k$)
- Is it a Plane? (300k$)
+++

---

## Mighty X Schwert mit Rückstoß X
Mighty X Schwerter ohne Rückstoß X können mit einem Rückstoß X Stock aus der Collector Chest zu einem Mighty X Schwert mit Rückstoß X kombiniert werden. Melde dich hierfür gerne bei einem Admin.

---

## Keep-Inventory Flag für PvP Arenen
Es ist möglich, für PvP-Arenen eine Keep-Inventory Flag zu erhalten, wodurch das Inventar beim Tod nicht verloren geht. In diesem Bereich darf sich nur die PvP-Arena befinden.

Eine Anfrage für eine Keep Inventory Flag kann mit den Koordinaten der Arena per Ticket im Discord gestellt werden.

---

## Joindate
Mit dem Befehl `/joindate` lässt sich in der Bauwelt anzeigen, wann man das erste Mal den Server betreten hat. Hinweis: Es darf kein Name, auch nicht der eigene, mit angegeben werden.