---
label: Pipes
layout: default
order: 498
icon: git-compare
---

# Pipes

Pipes aus dem Plugin CraftBook sind ein mächtiges Transport- und Sortiersystem für Items. Die Vorteile gegenüber herkömmlichen Systemen mit Hoppern sind vielfältig:
- Der Transport erfolgt stackweise und blitzschnell. Innerhalb einer halben Minute kann eine ganze Kiste in ein Lager transportiert und korrekt einsortiert werden.
- Items können problemlos in jede Richtung transportiert werden.
- Ein Pipes-System verbraucht beim Bau weniger Ressourcen als ein Hopper-System.
- Mehrere Items können in eine gemeinsame Kiste sortiert werden.
- Es ist möglich, nicht stackbare Items wie verzauberte Bücher oder Rüstungen zu sortieren.

!!!warning Wichtiger Hinweis zu Lags:
Wenn Pipes korrekt verwendet werden, sind sie wesentlich besser für die Serverperformance als Hoppersysteme. Die Beachtung der folgenden Hinweise ist aber wesentlich, um Lag zu vermeiden:
- Aktivierung des Pipe-Systems möglichst selten und nur bei Bedarf, zum Beispiel mit einer Komparator-Clock an der Eingangskiste (siehe unten)
- Insbesondere: Keine ständig laufenden Clocks an Pipes anschließen!
- Verwendung möglichst weniger Eingangskisten
- Keine Trichter in einem Pipesystem verwenden
- Möglichst kurze Pipes verwenden. Pipes, die in ungeladene Chunks gehen, sollen nur sehr selten und wenig verwendet werden.
!!!

---

## Ein einfaches Transportsystem
![](/images/pipes_1.png)
Der Screenshot zeigt eine Pipe, die auf Knopfdruck einen Stack Items von der Kiste unten links in die Kiste oben rechts transportiert.

Der **Eingang** besteht aus einem klebrigen Kolben, der zur Eingangskiste hinzeigt. Sobald dieser per Redstone-Signal aktiviert wird, "saugt" er die Items aus der Kiste in die Pipe hinein. Als Eingang können auch andere Blöcke mit Inventar dienen wie, Fässer, Öfen, Trichter etc.

Die **Pipe** selbst besteht aus Glasblöcken. Sie kann in jede beliebige Richtung führen und sich sogar verzweigen (wie es bei Sortiersystemen oft nötig sein wird).

Der **Ausgang** ist ein normaler Kolben, der zur Ausgangskiste hinzeigt. Er gibt die Items aus der Pipe in die Kiste hinein. Ein Ausgangskolben könnte die Items aber auch zum Beispiel in eine Shulkerkiste, ein Fass, einen Ofen (wird automatisch in den richtigen Slot gesetzt), einen Spender (wird automatisch aktiviert!) oder einen Trichter weitergeben. 

Eine Pipe sollte aber nicht in eine andere Pipe zeigen. Das bedeutet, dass kein normaler Kolben, der Items aus einer Pipe zieht, in eine andere Pipe (d. h. Glas) zeigen soll. Dies führt zu Systemen, die sich sehr inkonsistent verhalten und daher nicht einwandfrei funktionieren.

Der Transport eines Itemstacks dauert lediglich einen Tick (eine Zwanzigstelsekunde). Mit einem herkömmlichen Transportsystem würde dieser Transport fast eine halbe Minute brauchen.

!!!primary Bitte beachten:
Auch ein normaler Kolben wird als Bestandteil einer Pipe gewertet. Dies bedeutet, dass Kolben sich, genau wie Glas, untereinander Items weitergeben können. Daher ist es empfehlenswert, dass jedem einzelnen normalen Kolben im System ein Filterschild zugewiesen ist.
!!!

### Aktivierung des Eingangskolbens
Der klebrige Kolben kann auf folgende Arten aktiviert werden (siehe Screenshot):
-	Eine Redstonefackel, ein Hebel oder ein Knopf direkt daneben, darüber oder darunter.
-	Eine Redstoneleitung, die direkt neben dem Kolben verläuft.
-	Ein Beobachter, der in den Kolben hineinzeigt.

Andere, sonst aus Minecraft gewohnte Methoden funktionieren unter Umständen nicht.

![](/images/pipes_2.png)
Hier abgebildet ist ein einfacher Aufbau, welcher die Items in drei verschiedene Kisten sortiert. Der klebrige Kolben wird hier mit einem Knopfdruck aktiviert.

### Transportsysteme mit Verzweigungen
Sind mehrere Ausgangskisten an eine Pipe angeschlossen, so bevorzugt das System die Kisten, die näher an der Quelle liegen.
