---
label: MyPet
layout: default
order: 398
icon: squirrel
---

# MyPet

Das MyPet-Plugin erlaubt es dir, Mobs jeglicher Art (mit wenigen Ausnahmen) zu fangen und als Haustier zu halten. Diese unterstützen dich durch Kampfkraft, Beacon-ähnliche Effekte oder dienen als Reit- bzw. Flugtier.

---

## Mobs einfangen/zähmen
Je nach Mobart unterscheidet sich die Fangmethode. Monster müssen solange mit einer Leine geschlagen werden, bis ihr Leben 10% vom Maximum beträgt. Anschließend werden sie in Pets umgewandelt. Zähmbare Tiere müssen zunächst gezähmt werden. Anschließend genügt ein Schlag mit einer Leine, und sie werden in Pets umgewandelt.

Folgende Tiere sind nicht einfangbar:
- Wither
- Enderdrache
- Ghast
- Shulker

Gefangene Mobs können eingelagert, getauscht, gehandelt oder auch wieder freigelassen werden. Weitere Infos dazu findest du unter [Befehle](#befehle).

---

## Pet leveln
Um ein Pet zu leveln, muss dieses aktiv mit dir mitlaufen, während du Monster tötest. Das Pet erhält hierbei mehr Erfahrung, sollte es Mobs selbst töten.

---

## Klassen
![](/images/mypet_klassen.png)
Klassen verändern die Stärke (bzw. Fähigkeiten) eines Haustiers. Die Art der Bewegung, Erscheinung oder das Level-System des Haustiers ändert sich hierbei nicht. Jede Klasse legt seinen Fokus auf ein anderes Gebiet.

Steigt das Level deines Haustiers, so werden unterschiedliche Fähigkeiten gesteigert:
- Schaden
- Maximales Leben
- Lebensregeneration über Zeit
- Stärke, Dauer und Reichweite der Beacon-Effekte
- Reitgeschwindigkeit/Flugreichweite (Reitklasse)
- Vergrößertes Inventar (Farmklasse)

Viele Fähigkeiten und Zustände werden erst im späteren Verlauf freigeschaltet.

### Klasse auswählen
!!!primary Bitte beachten:
Sobald eine Klasse für ein Pet gewählt wurde, ist diese zwar ggf. erweiterbar, aber nicht revidierbar.
!!!

Um eine Klasse ("Skilltree") auszuwählen, nutze den Befehl /petchooseskilltree oder /pcst.

Bis auf wenige Ausnahmen (siehe Grafik) kann jedes Pet jede Klasse annehmen. Bei den unterschiedlichen Klassen spielt der Mobtyp keine Rolle, sondern alles wird über die einzelnen Klassen freigeschaltet.

### Grundklassen
+++ Reittier
Reittiere ermöglichen es dir, auf einem Mob zu reiten oder kurze Strecken zu fliegen. Sie eignen sich aber nur mäßig im Kampf. Um zu reiten, muss ein Rechtsklick mit einer Leine auf das Pet erfolgen (ab Level 5)

Mögliche Beacon-Effekte:
- Regeneration
- Geschwindigkeit

Maximales Level (inkl. Spezialisierungen):\
50 - 70

Pferde, Esel und Verwüster können diese Klasse nicht annehmen.

==- Spezialisierungen
#### Flugtier
Nur bei Mobs mit Flügeln möglich.\
Ermöglicht es, auf dem Reittier unendliche Strecken zu fliegen.

#### Pegasus
Eine Mischung zwischen Flug- und Landtier. Ermöglicht das verlängerte Fliegen, erhöhte Reitgeschwindigkeit gegenüber dem Flugtier.

#### Landtier
Das schnellste Reittier, kann jedoch nicht fliegen.
==-

+++ Kampftier
Nachts und in Duellen sind Kampftiere die besten Begleiter, da sie die höchste Kampfkraft besitzen.

Mögliche Beacon-Effekte:
- Stärke
- Feuerresistenz

Maximales Level (inkl. Spezialisierungen):\
70 - 80

==- Spezialisierungen
#### Krieger
Schnell, starker Nahkampf. Allgemeine Verbesserung der Grundklasse.

#### Schütze
Fernkampf der Kampfklasse. Hoher Schaden, hält aber vergleichsweise wenig aus. Keine Beacon-Effekte möglich.

#### Tank
Langsam, dafür umso robuster. Steckt einiges ein und leitet Schaden von seinem Besitzer auf sich um. Neben einer Verbesserung der Beacon-Effekte, zusätzlich Absorption.
==-

+++ Farmtier
Farmtiere helfen dem Spieler durch ein erweitertes Inventar, nützliche Effekte und eine mittlere Kampfkraft. Bei höhrerm Level können sie Items auch selbstständig aufsammeln.

Mögliche Beacon-Effekte:
- Absorption
- Eile
- Feuerresistenz

Maximales Level (inkl. Spezialisierungen):\
30 - 35
+++

### Spezialklassen
Bestimmte Mobarten besitzen besondere Klassen:

{.compact}
Mob/Klasse      | Erweiterung von...    | Fähigkeiten                                   | Beacon-Effekt
:---:           | :---:                 | :---:                                         | :---:
Husk            | Kriegerklasse         | Vegiftet seine Gegner zusätzlich.             | 
Eiswanderer     | Schützenklasse        | Verlangsamt seine Gegner zusätzlich.          | 
Lohe            | Schützenklasse        | Verbrennt seine Gegner zusätzlich.            | Feuerresistenz
Verwüster       | Tankklasse            | Stampft seine Gegner in Grund und Boden.      | 
Witherskelett   | Kriegerklasse         | Vergifte einen Gegner mit dem Withereffekt.   | 
Ertrunkener     |                       |                                               | Unterwasseratmung
Hase            |                       |                                               | Sprungkraft, Schnelligkeit, Glück
Enderman        |                       |                                               | Nachtsicht

Der Warden verschwindet beim Verwenden von /petrelease. Es gibt dann keine Möglichkeit, das freigelassene Pet erneut zu zähmen.

## Zustände
Ein Pet kann mit /petbehaviour in verschiedene Zustände versetzt werden:

{.compact}
:---:
Friendly	Dein Pet greift keine Mobs an, egal ob es selbst angegriffen wird.
Normal	Dein Pet greift nur an, wenn du/es von einem Gegner getroffen wirst/wird.
Aggressive	Dein Pet greift alles im Umkreis von 15 Blöcken an (Mobs sowie Spieler).
Farm	Dein Pet greift alle Mobs im Umkreis von 15 Blöcken um dich an.
Raid	Dein Pet greift nur feindliche Mobs an (Zombies,Skelette, etc) und keine Pets anderer Personen oder Villager.
Duel	Dein Pet greift Pets anderer Spieler an, deren Zustand auch auf "duel" gestellt ist (im Umkreis von 5 Blöcken).