---
label: AdminShop
layout: default
order: 598
icon: credit-card
---

# AdminShop

Im AdminShop kannst du ausgewählte Items an- und verkaufen. Um den AdminShop zu öffnen, verwende `/adminshop` oder `/as`.

---

## Limitierungen
Im AdminShop gibt es ein wöchentliches Limit an Items, die verkauft werden können. Zudem besteht die Möglichkeit, dass einzelne Items im Bezug auf das Kaufen oder Verkaufen limitiert sind. Diese Limits werden, sofern vorhanden, unterhalb der Preise eines Items aufgelistet. Ist dieses Limit erreicht, können vorerst keine Shopinteraktionen mit dem Item (+ einzelnes Kauf- oder Verkauflimit) getätigt werden.

Die Limitierungen beziehen sich immer auf dich selbst. Sie werden jeden Wochenanfang mit dem anstehenden Serverrestart (ca. 6:05 Uhr) zurückgesetzt.

---

## Aufbau
### Kategorien-Fenster
-![](/images/adminshop_kategorien.png)
Dies ist die Startseite des AdminShops. Hier kannst du deine persönlichen Shop-Informationen anzeigen und zwischen den einzelnen Kategorien wechseln.

<br>
<br>
<br>
<br>


### Item-Fenster einer Kategorie
-![](/images/adminshop_kategorie_item.png)
Innerhalb des Item-Fensters werden alle Items einer Kategorie aufgelistet. Die Items zeigen den Itemnamen und den Ankaufs- bzw. Verkaufspreis an.

Sollte der Verkaufs- oder Ankaufspreis mit einem roten “X” markiert sein, kann das Item nicht verkauft, bzw. angekauft werden. Ist eine einzelne Item-Limitierung vorhanden, wird diese unter dem Preis dargestellt.

### Aktions-Fenster eines Items
-![](/images/adminshop_aktion.png)
Wurde ein Item ausgewählt, wirst du in das Aktions-Fenster navigiert. Hier kannst du unter Berücksichtigung der Skalierungen der Interaktionen die Menge des zu kaufenden/verkaufenden Items erhöhen bzw. verkleinern. Dabei kannst du jeweils mit den Größenordnungen 1, 10 und 64 in beide Richtungen (Menge erhöhen/verkleinern) arbeiten.

Das Item in der Mitte zeigt die aktuell ausgewählte Menge, sowie den sich zusammensetzenden Preis, der für das Item ansteht. Unterhalb kann nun der Kauf bestätigt oder vollständig abgebrochen werden.

Wenn ein Inventar voll gekauft oder alle Items einer Art verkauft werden sollen, kann die Kiste unten rechts verwendet werden. Diese skaliert ebenfalls auf deine zur Verfügung stehenden Ressourcen und passt die Menge direkt an. Bei dem Kauf von “Inventargrößen” wird keine weitere Bestätigung (grüner Farbstoff) benötigt und der Kauf/Verkauf erfolgt sofort.

#### Skalierungen der Interaktionen
!!!warning Wichtiger Hinweis:
Die Skalierung der Interaktionen ist ein sehr komplexer Prozess, welcher den Adminshop so einfach und zeitsparend wie nur möglich machen soll. Die Funktionalität wurde sehr intensiv durchgeprüft. Dennoch sind Fehler nicht auszuschließen und folglich unverzüglich dem Team zu melden.
!!!

Der Adminshop enthält eine sehr präzise Abfrage in Abstimmung mit deiner zur Verfügung stehenden Ressourcen. Dass bedeutet, dass der Shop dir immer nur so viele Items verkauft bzw. abkauft, wie deine Ressourcen es zulassen - Andernfalls skaliert dieser die Menge auf das Maximum hinunter. Folgende Skalierungen nimmt der Shop vor:

##### Shop verkauft an Spieler (Kaufaktion):
- Inventarplatz
- Zur Verfügung stehendes Geld
- Einzelnes-Itemlimit (falls vorhanden)

##### Shop kauft von Spieler (Verkaufaktion):
- Item-Existenz im Inventar
- Globales Verkaufslimit
- Einzelnes-Itemlimit (falls vorhanden)