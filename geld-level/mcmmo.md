---
label: mcMMO
layout: default
order: 596
icon: goal
---

# mcMMO

mcMMO ist sehr umfangreich. Es beinhaltet ein Levelsystem für so ziemlich alle Tätigkeiten in Minecraft. Mit steigendem Level schaltet man sowohl permanente Vorteile als auch aktiv einsetzbare Spezialfähigkeiten frei. Bestenlisten sowohl für einzelne Skills (Tätigkeiten) als auch für das Gesamtlevel sind vorhanden.

!!! Abgrenzung von anderen Funktionen des Servers
Das Levelsystem und die XP von mcMMO haben nichts mit den Erfahrungspunkten aus Minecraft zu tun (also der grünen Anzeige über der Inventarleiste). Ebenso sind mcMMO und Jobs völlig unabhängig voneinander. Die Level, die man in einem Job hat, beeinflussen mcMMO nicht (und umgekehrt).
!!!

---

## Funktionsweise des Levelsystems
Leveln funktioniert mit dem Grundsatz "Learning by doing". Wenn du beispielsweise Erde abbaust, erhältst du XP und Level für den dazu passenden Skill "Graben".

Zu Beginn levelst du deine Skills sehr schnell (besonders stark bemerkst du dies wahrscheinlich beim Minen). Dieser Fortschritt verlangsamt sich aber mit höheren Leveln extrem.

Wenn du bestimmte Levelgrenzen überschreitest, schaltest du sowohl passive Fähigkeiten frei, die ständig aktiv sind (z.B. höhere Dropraten beim Abbauen), als auch Spezialfähigkeiten, die du gezielt einsetzen kannst. Um diese zu aktivieren, musst du das passende Werkzeug (z.B. ein Schwert) zunächst "aufladen". Dies geschieht, indem du schleichst und einen Rechtsklick ausführst. Über der Inventarleiste erscheint dann ein Text (z.B. "Dein Schwert ist bereit"). Nun kann die Spezialfähigkeit durch Benutzen des Werkzeuges aktiviert werden.

Spezialfähigkeiten halten eine gewisse Zeit lang an, die vom Level im jeweiligen Skill abhängt. Nach Ablauf dieser Zeit ist die Fähigkeit auf einem Cooldown, bevor sie erneut verwendet werden kann.

Eine Liste der Skills sowie der passiven und aktiven Fähigkeiten findest du unten auf der Seite. Mehr Details sind im [inoffiziellen Wiki](https://mcmmo.fandom.com/wiki/McMMO_Wiki) oder in der Ingame-Hilfe zu finden‌.

---

## Befehle
`/mcmmo`\
Öffnet das Hauptmenü, über welches alle Statistiken, Skills und Ranglisten abrufbar sind.

`/mcmmo help`\
Zeigt die wichtigsten Befehle an.

`/mcstats`\
Zeigt eine Liste aller Skills und der derzeitigen Level des Spielers an. Zeigt auch das derzeitige Gesamtlevel an.

`/<skillname>` (z.B. /graben oder /zähmen)\
Zeigt genaue Statistiken zu einem speziellen Skill an – derzeitiges Level, freigeschaltete passive und aktive Fähigkeiten, und ihre derzeitigen Werte.

`/<skillname> ? <seite>`\
Zeigt detaillierte Hilfe zu einem speziellen Skill an.

`/mctop <seite>`\
Zeigt die Bestenliste der Gesamtlevel aller Spieler an.

`/mctop <skillname> <seite>`\
Zeigt die Bestenliste der Level in einem bestimmten Skill aller Spieler an.

`/mcability`\
Deaktiviert das "Aufladen" per Schleich-Rechtsklick, falls es als störend empfunden wird, oder schaltet es wieder ein. Aktive Spezialfähigkeiten können mit ausgeschaltetem Aufladen nicht verwendet werden.

`/mmoxpbar disable`\
Deaktiviert die mcMMO-Erfahrungsleiste für alle Skills.

`/mmoxpbar hide <skillname>`\
Versteckt die Erfahrungsleiste von mcMMO für den angegebenen Skill.

`/mmoxpbar reset`\
Setzt die Einstellungen zu den mcMMO-Erfahrungsleisten zurück.

`/inspect <spielername>`\
Wenn sich der Spieler in der Nähe befindet, kannst du mit diesem Befehl seine mcMMO-Level einsehen.

---

## Liste der Skills
Skillname | Leveln durch... | Features (Zusammenfassung) | Hinweise
:---: | --- | --- | ---
Akrobatik   | Erleiden von Fallschaden | Verringert mit einer gewissen levelabhängigen Chance Fallschaden. Während des Fallens die Schleichen-Taste gedrückt zu halten, verringert den Schaden weiter. Ferner besteht eine Chance, im Kampf geringeren Schaden zu nehmen.	| Leveln funktioniert nur, wenn /fly deaktiviert ist.
Alchemie    | Brauen von Tränken | Es werden zunehmend viele neue Rezepte für in Minecraft sonst nicht erhältliche Tränke freigeschaltet. Tränke werden außerdem zunehmend schneller gebraut. | 
Angeln      | Erfolgreiches Verwenden von Angelruten | Neben allmählichen Upgrades für das Angeln im Wasser an sich (häufigere und bessere Schätze, weniger Wartezeit) sättigt geangeltes Essen auch besser. Mit hinreichend hohem Level kann man Mobs mit einer Angel mit einer gewissen Chance ihre Drops entreißen, aber sowohl der Mob als auch die Angel werden dabei stark beschädigt. | mcMMO bringt sein eigenes Angelsystem mit, das das Vanilla-Angelsystem ersetzt. Drops werden also anders (und am Anfang insbesondere schlechter) sein als aus Vanilla-Minecraft gewohnt – Übersicht siehe [hier](#angel-drops).
Axtkampf    | Schlagen von Mobs mit Äxten | Äxte verursachen mit höheren Leveln zunehmend viel Schaden. Sie werden besonders gut darin, die Haltbarkeit von Rüstungen zu schmelzen. Die aufladbare Spezialfähigkeit verwandelt den Angriff der Axt in einen Flächenangriff. | 
Bergbau	    | Abbauen von Blöcken, die mit Spitzhacken abzubauen sind, wie Stein oder Erzblöcke	| Mit einer zunehmend großen Chance droppen relevante Blöcke nicht nur einmal, sondern gleich doppelt. Die aufladbare Spezialfähigkeit versieht die Spitzhacke für kurze Zeit mit zusätzlicher Effizienz und abgebaute Blöcke können sogar dreifach droppen. Man kann die Fähigkeit freischalten, TNT aus der Ferne zu zünden, indem man im Schleichen und weit entfernt mit einem Feuerzeug einen Rechtsklick auf das TNT ausführt. Höhere Level vergrößern den Schaden und die Effizienz dieser Explosionen.

---

## Besondere Drops
### Angel-Drops
Angeln verwendet ein Rang-System, bei dem du je nach Level einem Rang zugeordnet wirst. Zusätzlich dazu ist der mögliche Loot in sieben verschiedene Seltenheitsstufen aufgeteilt. Daraus ergibt sich der beim Angeln zu erhaltende Loot sowie die Wahrscheinlichkeit, mit der die verschiedenen Items geangelt werden können.

+++ Drop-Chancen
Hier sind die Seltenheitsstufen mit den jeweiligen Drop-Chancen pro Rang aufgelistet. Alle Angaben sind in Prozent.


+++ Drop-Items
Hier sind die Items aufgelistet, die in der jeweiligen Seltenheitsstufe gedroppt werden können. Die Menge, die je Item gedroppt werden kann (falls das Item stackbar ist), variiert. Bei Rüstungsteilen, Werkzeugen und Waffen sind mit steigender Seltenheit auch bessere Verzauberungen möglich.


+++

### Graben-Drops
Auch beim Graben droppen je nach Level spezielle Items:

---

## mcMMO Parties
mcMMO Parties bieten dir die Möglichkeit, eine Gruppe mit anderen Spielern zu erstellen. Diese bringen einige Vorteile wie einen eigenen Chat und das teilen von XP in einem bestimmten Umkreis mit sich. Details zum Party-System findest du im [mcMMO-Wiki](https://mcmmo.fandom.com/wiki/Parties).

### Befehle
`/party create <partyname>`\
Erstellen einer Party.

`/party password <passwort>`\
Schützt deine Party mit einem Passwort.

`/party invite <spielername>`\
Lädt den angegebene Spieler zu deiner Party ein.

`/party kick <spielername>`\
Entfernt den angegebenen Spieler aus deiner Party.

`/party leader <spielername>`\
Überträgt deine Party auf den angegebenen Spieler.

`/party disband`\
Löst deine Party auf.

`/party`\
Zeigt alle Infos zu deiner Party an. 

### Besondere Funktionen
Besondere Funktionen der mcMMO Parties können erst ab einem spezifischen Party-Level genutzt werden:

{.compact}
Funktion	        | Ab Level
---                 | ---
Gruppenchat         | 1        
Gruppenteleport     | 2
Bündnisse           | 5
Items teilen        | 8
Erfahrung teilen    | 10
