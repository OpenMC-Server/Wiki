---
label: mcMMO
layout: default
order: 595
icon: goal
---

# mcMMO

[!badge :white_check_mark: Ingame-Tutorial verfügbar: `/warp tutorial_mcmmo`]

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

`/mcmmo-cooldowns`\
Deaktiviert/Aktiviert jeweils den Cooldown von Spezialfähigkeiten, der in deiner Actionbar angezeigt wird.

`/mcmmo-drops`\
Deaktiviert Bonus-Drops, die du aus den Fähigkeiten nebenbei erhältst.

---

## Liste der Skills
Skillname       | Leveln durch...   | Features (Zusammenfassung)    | Hinweise
:---:           | ---               | ---                           | ---
Akrobatik       | Erleiden von Fallschaden | Verringert mit einer gewissen levelabhängigen Chance Fallschaden. Während des Fallens die Schleichen-Taste gedrückt zu halten, verringert den Schaden weiter. Ferner besteht eine Chance, im Kampf geringeren Schaden zu nehmen.	| Leveln funktioniert nur, wenn /fly deaktiviert ist.
Alchemie        | Brauen von Tränken | Es werden zunehmend viele neue Rezepte für in Minecraft sonst nicht erhältliche Tränke freigeschaltet. Tränke werden außerdem zunehmend schneller gebraut. | 
Angeln          | Erfolgreiches Verwenden von Angelruten | Neben allmählichen Upgrades für das Angeln im Wasser an sich (häufigere und bessere Schätze, weniger Wartezeit) sättigt geangeltes Essen auch besser. Mit hinreichend hohem Level kann man Mobs mit einer Angel mit einer gewissen Chance ihre Drops entreißen, aber sowohl der Mob als auch die Angel werden dabei stark beschädigt. | mcMMO bringt sein eigenes Angelsystem mit, das das Vanilla-Angelsystem ersetzt. Drops werden also anders (und am Anfang insbesondere schlechter) sein als aus Vanilla-Minecraft gewohnt – Eine Übersicht findest du [hier](#angel-drops).
Axtkampf        | Schlagen von Mobs mit Äxten | Äxte verursachen mit höheren Leveln zunehmend viel Schaden. Sie werden besonders gut darin, die Haltbarkeit von Rüstungen zu schmelzen. Die aufladbare Spezialfähigkeit verwandelt den Angriff der Axt in einen Flächenangriff. | 
Bergbau	        | Abbauen von Blöcken, die mit Spitzhacken abzubauen sind, wie Stein oder Erzblöcke	| Mit einer zunehmend großen Chance droppen relevante Blöcke nicht nur einmal, sondern gleich doppelt. Die aufladbare Spezialfähigkeit versieht die Spitzhacke für kurze Zeit mit zusätzlicher Effizienz und abgebaute Blöcke können sogar dreifach droppen. Man kann die Fähigkeit freischalten, TNT aus der Ferne zu zünden, indem man im Schleichen und weit entfernt mit einem Feuerzeug einen Rechtsklick auf das TNT ausführt. Höhere Level vergrößern den Schaden und die Effizienz dieser Explosionen. | 
Bergung	        | Leveln von Angeln und Reparatur | Mit einem mcMMO-Goldamboss (das heißt einem platzierten Goldblock) können Rüstungen und Werkzeuge durch Rechtsklick zerlegt werden, um die Rohmaterialien zumindest teilweise zurückzuerhalten. Mit höheren Leveln kann man auch die Verzauberungen verwerten, also zumindest teilweise in Form von verzauberten Büchern zurückerhalten. | 
Bogenschießen   | Treffen von Mobs mit Pfeil und Bogen, oder per Armbrust | Neben dem offensichtlichen höheren Schaden von Bögen mit höheren Leveln bekommen Treffer im PVP das Potenzial, andere Spieler kurzzeitig mit Übelkeit zu belegen. Mit zunehmend hohen Chancen verbraucht man keine Pfeile beim Abschießen, auch ohne Unendlichkeit-Verzauberung. Armbrüste profitieren allerdings nicht von diesen Änderungen. | Entfernung des Gegners und angerichteter Schaden beeinflusst die erhaltenen XP
Faustkampf      | Schlagen von Mobs mit der Hand | Mit hohen Leveln verursachen die bloßen Hände des Spielers viel mehr Schaden als in Vanilla-Minecraft. Indem die Hand aufgeladen und aktiviert wird, erhält man für kurze Zeit nicht nur einen zusätzlichen Schadensboost, sondern kann auch üblicherweise von Hand abbaubare Blöcke (Erde, Sand etc.) extrem schnell mit der Hand abbauen. Weitere einzigartige Fähigkeiten beinhalten das gelegentliche automatische Abwehren von Pfeilen, sowie die Chance, einen PVP-Gegner zu entwaffnen, wenn man ihn unbewaffnet bekämpft. Man selbst wird mit hohen Leveln außerdem unempfindlicher gegen Entwaffnungen. | 
Graben	        | Abbauen von Blöcken, die mit Schaufeln abzubauen sind, wie Sand oder Erde | Oft macht sich dieser Skill für neue Spieler als erstes bemerkbar. Beim Abbauen von erdartigen Blöcken erhält man bei genügend hohen Leveln Chancen, andere Dinge als nur den Block selbst zu erhalten. Dazu gehören Glowstonestaub, Knochen oder Pilze schon bei recht niedrigen Leveln, aber auch Quartz und sogar Diamanten bei hohen Leveln. Schaufeln kann man aufladen und dann ähnlich wie beim Bergbau für eine kurze Zeit mehr Effizienz-Level auf ihr erhalten. In dieser Zeit droppen auch die erwähnten "Schätze" häufiger. | Abbauen von Hand levelt auch. Einige "Schätze", die aus Gras und Erde droppen können, wurden auf Spielerwunsch wegen Inventarspam deaktiviert (zum Beispiel Schallplatten) – Eine Übersicht findest du [hier](#graben-drops).
Holzfällen	    | Abbauen von Baumstämmen | Genau wie Bergbau erhält man auch in diesem Skill allmählich immer mehr doppelte Drops aus abgebauten Stämmen. Äußerst praktisch ist die aufladbare Fähigkeit, die einem für kurze Zeit erlaubt, Bäume mit einem einzigen Linksklick vollständig zu fällen. Mit hinreichend hohem Level kann man außerdem dauerhaft Blätter mit Äxten extrem schnell abbauen. | Abbauen von Hand levelt auch
Kräuterkunde	| Abbauen von Gras, Blumen, Korallen, Ackerpflanzen, ... | Die aktive Spezialfähigkeit dieses Skills wird durch Aufladen einer Hacke verwendet. Sie ist zweigeteilt: Einerseits werden alle Felder, die man in der kurzen Aktivitätszeit aberntet, automatisch nachgepflanzt und bringen bis zu dreifachen Ertrag. Andererseits erlaubt einem die aktivierte Hacke, Steinblöcke durch Linksklick in bemooste Varianten zu verwandeln, oder Erde zu begrünen. Dies verbraucht Samen aus dem Inventar des Spielers. Auch ohne die Spezialfähigkeit bringen Felder zunehmend viel Ernte ein und können sich manchmal selbst nachpflanzen. Was auch immer geerntet wird, sättigt mit steigendem Level immer besser. Baut man ausgewählte Pflanzen oder pflanzenverwandte Blöcke mit einem Schwert ab, können bei hohen Leveln unerwartete Drops entstehen. | Bäume fallen nicht unter Kräuterkunde
Reparatur       | Reparieren von Werkzeugen mit dem mcMMO-Amboss, Einschmelzen von Eisen und Gold | Der "mcMMO-Amboss" ist nicht der Minecraft-Amboss, sondern ein platzierter Eisenblock. Ein Werkzeug wird repariert, indem man mit dem Werkzeug in der Hand und entsprechenden Materialien im Inventar auf den Eisenblock rechtsklickt. Vorsicht: Standardmäßig gehen Verzauberungen dabei verloren, aber mit hohen Leveln hat man Chancen, sie zumindest teilweise zu retten. | Der Skill für sich genommen ist in den neueren Minecraft-Versionen wenig nützlich, Minecraft-Ambosse sind meist überlegen
Schmelzen       | Leveln von Bergbau und Reparatur | Dieser Skill bringt levelabhängige passive Boni auf das Einschmelzen von Erzen und einigen anderen Items. Die Brenndauer des Brennstoffes wird erhöht, die Entnahme der fertig eingeschmolzenen Items bringt mehr (Minecraft-)XP ein, und es bestehen Chancen, dass Items während des ganzen Vorgangs den doppelten Ertrag bringen. | Nicht alle Schmelzvorgänge profitieren von diesem Skill, erwiesenermaßen z.B. Stein zu glattem Stein wird unverändert gebrannt.
Schwert         | Schlagen von Mobs mit Schwertern | Wie im Axtkampf auch kann man sein Schwert mit einer Spezialfähigkeit aufladen, die ihm für kurze Zeit Flächenschaden verleiht. Hohe Level bringen zwar nicht bei jedem Schwerthieb zusätzlichen Schaden, aber dafür gute Chancen, Blutung beim Gegner auszulösen. Hohe Level versehen den Spieler zudem mit einem permanenten Dornen-Effekt, der mit einer gewissen Chance aktiviert wird. | 
Zähmen          | Zähmen von Pferden oder Ozelots, Kämpfen mit gezähmten Wölfen	| Unabhängig vom Level kann man beliebige Minecraft-Haustiere (nicht zu verwechseln mit [Pets](/besondere-funktionen/mypet.md)) mit einem Knochen schlagen, um deren Gesundheit und Besitzer zu ermitteln. Das Haustier bleibt dabei unversehrt. Mit einem Schleich-Linksklick mit 10 Knochen, rohen Fischen, oder Äpfeln in der Hand kann ein Wolf, eine Katze oder ein Pferd beschworen werden, das 4 Minuten lang an der Seite des Spielers steht. Level in diesem Skill verbessern gezähmte Wölfe teils dramatisch, mit höherem Schaden, Chance auf Selbstregeneration sowie Rückstoß- und Blutungseffekte in Kämpfen, und Resistenzen gegen Kakteen, Lava, Stürze und Explosionen. | 

---

## Besondere Drops
### Angel-Drops
Angeln verwendet ein Rang-System, bei dem du je nach Level einem Rang zugeordnet wirst. Zusätzlich dazu ist der mögliche Loot in sieben verschiedene Seltenheitsstufen aufgeteilt. Daraus ergibt sich der beim Angeln zu erhaltende Loot sowie die Wahrscheinlichkeit, mit der die verschiedenen Items geangelt werden können.

+++ Drop-Chancen
Hier sind die Seltenheitsstufen mit den jeweiligen Drop-Chancen pro Rang aufgelistet. Alle Angaben sind in Prozent.

{.compact}
Seltenheit | Rang 1 (Level 0) | Rang 2 (Level 125) | Rang 3 (Level 250) | Rang 4 (Level 375) | Rang 5 (Level 500) | Rang 6 (Level 625) | Rang 7 (Level 700) | Rang 8 (Level 875+)
:---:       | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
Common      | 7,5   | 6,5	| 3,5	| 2	    | 1,5	| 1	    | 0,25	| 0,1
Uncommon    | 1,25	| 1,75	| 2,75	| 3,5	| 3,75	| 3,25	| 2,75	| 1,5
Rare        | 0,25	| 0,75	| 1,25	| 2,25	| 2,5	| 3,75	| 4	    | 6
Epic        | 0,15	| 0,5	| 1	    | 1,5   | 2	    | 2,5	| 5	    | 7,5
Legendary   | 0,1	| 0,15	| 0,35	| 1	    | 1	    | 1,5	| 2,5	| 5
Mythic      | 0,01	| 0,02	| 0,02	| 0,02	| 0,02	| 0,05	| 0,1	| 0,25
Record      | 0,1	| 0,2	| 0,25	| 0,35	| 0,5	| 0,5	| 0,5	| 0,75
Total       | 9,36	| 9,87	| 9,12	| 10,62	| 11,27	| 12,55	| 15,1	| 21,1
Fische      | 90,64	| 90,13	| 90,88	| 89,38	| 88,73	| 87,45	| 84,9	| 78,9

+++ Drop-Items
Hier sind die Items aufgelistet, die in der jeweiligen Seltenheitsstufe gedroppt werden können. Die Menge, die je Item gedroppt werden kann (falls das Item stackbar ist), variiert. Bei Rüstungsteilen, Werkzeugen und Waffen sind mit steigender Seltenheit auch bessere Verzauberungen möglich.

{.compact}
Seltenheit  | Items
:---:       | ---
Common      | Lederrüstung, Lapislazuli, Seerosenblatt, Leder, Faden, Knochen, Tintenbeutel, Feuerstein, Papier, Tonklumpen
Uncommon    | Eisenbarren, Goldbarren, Diamant, Lapislazuli, Seerosenblatt, Leder, Faden, Knochen, Tintenbeutel, Feuerstein, Papier, Tonklumpen
Rare        | Eisenwerkzeuge, Eisenschwert, Bogen, Eisenbarren, Goldbarren, Lapislazuli, Namensschild, Seerosenblatt, Leder, Faden, Knochen, Tintenbeutel, Feuerstein, Papier, Tonklumpen, Prismarinkristall, Prismarinscherbe
Epic        | Eisenrüstung, Diamant, Namensschild, Ghastträne, Spinnennetz, Seelaterne, Prismarinkristall, Prismarinscherbe
Legendary   | Diamantrüstung, Diamantwerkzeuge, Diamantschwert, Verzaubertes Buch, Netheritplatte, Nautilusschale, Spinnennetz, Seelaterne, Nasser Schwamm
Mythic      | Netheritrüstung, Netheritwerkzeuge, Netheritschwert, Nasser Schwamm, Disc - Otherside
Record      | Alle anderen Schallplatten

+++

### Graben-Drops
Auch beim Graben droppen je nach Level spezielle Items:

{.compact}
Item            | Ab Level  | Droppt aus...                                                                         | Drop-Chance (%)
:---:           | :---:     | ---                                                                                   | :---:
Glowstonestaub  | 50        | Erde, Grobe Erde, Grasblock, Podsol, Myzel, Sand, Roter Sand                          | 5
Schwarzpulver   | 100       | Kies                                                                                  | 10
Schleimball     | 150       | Ton                                                                                   | 0,1
Knochen         | 200       | Kies                                                                                  | 10
Faden           | 250       | Ton                                                                                   | 5
Apfel           | 250       | Grasblock, Myzel                                                                      | 0,1
Namensschild    | 250       | Erde, Grobe Erde, Grasblock, Podsol, Myzel, Kies, Ton, Sand, Roter Sand, Seelensand   | 0,05
Diamant         | 350       | Erde, Grobe Erde, Grasblock, Podsol, Myzel, Kies, Ton, Sand, Roter Sand, Seelensand   | 0,13
Eimer           | 500       | Ton                                                                                   | 5
Brauner Pilz    | 500       | Erde, Grobe Erde, Grasblock, Podsol, Myzel                                            | 0,5
Seelensand      | 650       | Sand, Roter Sand                                                                      | 0,5
Spinnennetz     | 750       | Ton                                                                                   | 5
Kuchen          | 750       | Erde, Grobe Erde, Grasblock, Podsol, Myzel, Kies, Ton, Sand, Roter Sand, Seelensand   | 0,05
Quartz          | 850       | Erde, Grobe Erde, Grasblock, Podsol, Myzel, Kies, Sand, Roter Sand, Seelensand        | 0,5

---

## mcMMO Parties
mcMMO Parties bieten dir die Möglichkeit, eine Gruppe mit anderen Spielern zu erstellen. Diese bringen einige Vorteile wie einen eigenen Chat und das teilen von XP in einem bestimmten Umkreis mit sich. Details zum Party-System findest du im [mcMMO-Wiki](https://mcmmo.fandom.com/wiki/Parties).

### Befehle
`/party create <partyname>`\
Erstellt eine Party.

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
