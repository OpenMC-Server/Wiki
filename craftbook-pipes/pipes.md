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