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

Um einen solchen Lift zu erzeugen, werden zwei Schilder benötigt, welche übereinander platziert werden müssen (Zwischenblöcke spielen dabei keine Rolle). Auf das obere Schild, in der zweiten Zeile muss hierbei `[Lift Down]` und auf das untere Schild in die zweite Zeile `[Lift Up]` geschrieben werden.

Die erste Zeile des Schildes kann genutzt werden, um das entsprechende Stockwerk zu benennen und dies im Chat anzeigen zu lassen. Lift-Schilder können außerdem durch einen Knopf aktiviert werden, welcher sich auf der gegenüberliegenden Seite des Blocks befinden muss, an welchem das Schild platziert wurde.

Beachte: Der Lift kann nur gerade hinauf oder hinunter teleportieren. D.h. solltest du vom Schild einige Blöcke entfernt stehen und diese in der anderen Etage nicht existieren oder blockiert sein, ist eine Teleportation nicht möglich („Es gibt kein Stockwerk an deiner Position“). Diese Nachricht bedeutet also nicht automatisch, dass die Schilder falsch platziert wurden.

---

## Gate-Schilder
Die Gate-Schilder ermöglichen es dir, mithilfe eines Schildes (oder zweien, sollte das Gate von beiden Seiten aus verwendet werden können) eine Art Tor zu erstellen, welches per Rechtsklick auf das zugehörige Schild geöffnet und geschlossen werden kann.

Um ein Gate zu erstellen, müssen Zäune übereinander platziert werden, wobei die Oberseite des gewünschten Tores mit anderen Blöcken abzudecken ist. Die Größe und Form der Tore kann variieren, hierbei beträgt die Breite maximal 14 und die Höhe maximal 12 Blöcke. Daneben wird ein Schild platziert, in dessen zweite Zeile `[Gate]` geschrieben wird. Soll das Tor von beiden Seiten aus bedient werden können, kann auf der anderen Seite am selben Block des ersten Gate-Schildes ein weiteres platziert werden.

Die Zahl in der 4. Zeile des Schildes gibt an, wie viele Zäune im Gate-Lager vorhanden sind, um dieses wiederaufzubauen. Es ist möglich, die Gate-Schilder mittels Redstone-Signal zu betätigen – ein aktiver Input erstellt dabei das Gate, ein inaktiver entfernt es.

Für ein Gate können alle Zäune sowie Glasscheiben, Mauern und Eisengitter verwendet werden. Das Gate darf nur aus einem Material bestehen, z.B. verschiedene Zaunarten in einem Gate zu mischen funktioniert nicht.

||| Geschlossenes Gate
![](/images/gate_closed.png)
||| Geöffnetes Gate
![](/images/gate_open.png)
||| Geöffnetes Gate ohne Umrandung
![](/images/gate_open_2.png)
|||

---

## Wireless-Redstone
Die beiden Schaltungen MC1110 und MC1111 geben dir die Möglichkeit, „Wireless Redstone“ („Kabelloses Redstone“) zu verwenden. Die genaue Verwendung wird gut in der offiziellen Dokumentation von CraftBook beschrieben:
- MC1110 „Transmitter“ („Sender“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1110/)
- MC1111 „Receiver“ („Empfänger“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1111/)

Beachte: Vor dem „Transmitter“ muss die Redstone Leitung mindestens zwei Blöcke lang sein, da die Schaltung ansonsten unter Umständen nicht funktioniert. Am Receiver muss ggf. ein “s” ergänzt werden ("[MC1111]s"), um die Funktionalität zu gewährleisten.

---

## Redstone-Jukebox
Jukeboxen können mit Redstone gesteuert werden, um eingelegte Schallplatten zu starten. Das Redstone-Signal startet die Schallplatte auch neu, wenn sie bereits läuft. Das Stoppen ist aufgrund von Limitierungen nicht möglich, dies passiert weiterhin nur dann, wenn die Schallplatte beendet ist oder ausgeworfen wird.
