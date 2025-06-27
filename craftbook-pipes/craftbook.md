---
label: CraftBook
layout: default
order: 499
icon: gear
---

# CraftBook

[!badge :white_check_mark: Ingame-Tutorial verfügbar: `/warp tutorial_craftbook`]

Mit CraftBook gibt es eine Reihe an nützlichen Funktionen auf dem Server, welche das Spielgeschehen deutlich erweitern und vereinfachen.\
Pipes werden auf einer [eigenen Seite](/craftbook-pipes/pipes.md) erklärt. Alle weiteren CraftBook Funktionen findest du auf der aktuellen Seite.

---

## Lift-Schilder
Die Lift-Schilder ermöglichen es dir, mithilfe zweier Schilder eine Art Aufzug zu erzeugen, welcher dich zwischen verschiedenen Stockwerken teleportieren kann.

Um einen solchen Lift zu erzeugen, werden zwei Schilder benötigt, welche übereinander platziert werden müssen (Zwischenblöcke spielen dabei keine Rolle). Auf das obere Schild, in der zweiten Zeile muss hierbei `[Lift Down]` und auf das untere Schild in die zweite Zeile `[Lift Up]` geschrieben werden. Ebenfalls kann `[Lift UpDown]` genutzt werden, um einen Transport in beide Richtungen zu ermöglichen.

Die erste Zeile des Schildes kann genutzt werden, um das entsprechende Stockwerk zu benennen und dies im Chat anzeigen zu lassen. Lift-Schilder können außerdem durch einen Knopf aktiviert werden, welcher sich auf der gegenüberliegenden Seite des Blocks befinden muss, an welchem das Schild platziert wurde.

Beachte: Der Lift kann nur gerade hinauf oder hinunter teleportieren. D.h. solltest du vom Schild einige Blöcke entfernt stehen und diese in der anderen Etage nicht existieren oder blockiert sein, ist eine Teleportation nicht möglich („Es gibt kein Stockwerk an deiner Position“). Diese Nachricht bedeutet also nicht automatisch, dass die Schilder falsch platziert wurden.

---

## Gate-Schilder
Die Gate-Schilder ermöglichen es dir, mithilfe eines Schildes (oder zweien, sollte das Gate von beiden Seiten aus verwendet werden können) eine Art Tor zu erstellen, welches per Rechtsklick auf das zugehörige Schild geöffnet und geschlossen werden kann.

Um ein Gate zu erstellen, müssen Zäune übereinander platziert werden, wobei die Oberseite des gewünschten Tores mit anderen Blöcken abzudecken ist. Die Größe und Form der Tore kann variieren, hierbei beträgt die Breite maximal 14 und die Höhe maximal 12 Blöcke. Daneben wird ein Schild platziert, in dessen zweite Zeile `[Gate]` geschrieben wird. Soll das Tor von beiden Seiten aus bedient werden können, kann auf der anderen Seite am selben Block des ersten Gate-Schildes ein weiteres platziert werden.

Es ist möglich, die Gate-Schilder mittels Redstone-Signal zu betätigen – ein aktiver Input erstellt dabei das Gate, ein inaktiver entfernt es.

Für ein Gate können alle Zäune sowie Glasscheiben, Mauern und Eisengitter verwendet werden. Das Gate darf nur aus einem Material bestehen, z.B. verschiedene Zaunarten in einem Gate zu mischen funktioniert nicht.

Sollten nicht ausreichend Blöcke für das Gate zur Verfügung stehen, können diese mit einem Klick auf das Schild mit dem Item nachgefüllt werden.

||| Geschlossenes Gate
![](/images/gate_closed.png)
||| Geöffnetes Gate
![](/images/gate_opened.png)
|||

---

## Bridge-Schilder
Die Bridge-Schilder ermöglichen es dir, mithilfe eines Schildes (oder zweien, sollte die Bridge von beiden Seiten aus verwendet werden können) eine Brücke zu erstellen, welche per Rechtsklick auf das zugehörige Schild ausgefahren oder eingefahren werden kann.

Um eine Bridge zu erstellen, ist es wichtig, dass der unter dem Schild gesetzte Block auch dem Material entspricht, mit dem die Brücke gebaut wird. Das Material sollte sich dabei von anderen Blöcken links und rechts von der Brücke unterscheiden.

Das Schild wird in der zweiten Zeile mit `[Bridge]` beschriftet.  Das gleiche kann bei Bedarf auf der anderen Seite der Brücke vorgenommen werden, sodass eine Breite von 5 Blöcken vorgegeben ist und eine Länge von maximal 30 Blöcken möglich ist. Das zweite Schild kann auch mit `[Bridge End]` beschriftet werden, um die Brücke nur von einer Seite aus umschaltbar zu machen.

Für eine Brücke kann eine Vielzahl an Blöcken (auch Stufen) benutzt werden. Solltest du eine sinnvolle Blockart im Sortiment vermissen, kannst du diese gerne über das Forum als Vorschlag einreichen.

Sollten nicht ausreichend Blöcke für die Bridge zur Verfügung stehen, können diese mit einem Klick auf das Schild mit dem Item nachgefüllt werden.

||| Geschlossene Bridge
![](/images/bridge_closed.png)
||| Geöffnete Bridge
![](/images/bridge_opened.png)
|||

---

## Wireless-Redstone
Die beiden Schaltungen MC1110 und MC1111 geben dir die Möglichkeit, „Wireless Redstone“ („Kabelloses Redstone“) zu verwenden. Die genaue Verwendung wird gut in der offiziellen Dokumentation von CraftBook beschrieben:
- MC1110 „Transmitter“ („Sender“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1110/)
- MC1111 „Receiver“ („Empfänger“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1111/)

Beachte: Vor dem „Transmitter“ muss die Redstone Leitung mindestens zwei Blöcke lang sein, da die Schaltung ansonsten unter Umständen nicht funktioniert. Am Receiver muss ggf. ein “s” ergänzt werden ("[MC1111]s"), um die Funktionalität zu gewährleisten.

||| Schilder „Sender" und „Empfänger"
![](/images/SenderEmpfänger.png)
||| Weiterleitung vom Signal
![](/images/SignalEmpfang.png)
---

## Redstone-Jukebox
Jukeboxen können mit Redstone gesteuert werden, um eingelegte Schallplatten zu starten. Das Redstone-Signal startet die Schallplatte auch neu, wenn sie bereits läuft. Das Stoppen ist aufgrund von Limitierungen nicht möglich, dies passiert weiterhin nur dann, wenn die Schallplatte beendet ist oder ausgeworfen wird.

