---
label: MyPet
layout: default
order: 398
icon: squirrel
---

# MyPet

[!badge :white_check_mark: Ingame-Tutorial verfügbar: `/warp tutorial_pets`]

Das MyPet-Plugin erlaubt es dir, Mobs jeglicher Art (mit wenigen Ausnahmen) zu fangen und als Haustier zu halten. Diese unterstützen dich durch Kampfkraft, Beacon-ähnliche Effekte oder dienen als Reit- bzw. Flugtier.

---

## Mobs einfangen/zähmen
Jeder Mobtyp ist einer Stärkekategorie (S0-S5) zugeordnet und erhält basierend auf seiner Art eine individuelle Fähigkeitsklasse.
Eine detaillierte Übersicht findet sich hier: [Stärke-Kategorien](#stärke-kategorien).

Je nach Mob-Typ und Stärke-Kategorie unterscheiden sich die Anforderungen zum Einfangen des Pets:
- Erreichen nötiger mcMMO-Level in bestimmten Skills
- Der Mob muss unter einer definierten Prozentzahl an Lebenspunkten liegen (HP-Grenze)
- Je nach Stärke des Mobs variiert die Wahrscheinlichkeit den Mob mit einem Schlag tatsächlich einzufangen (Chance)

Zähmbare Tiere müssen zunächst gezähmt werden. Mobs, welche durch einen Spieler erzeugt werden können (Eisengolem/Schneegolem) müssen eigenständig erbaut werden.

Wenn alle Anforderungen erfüllt sind, können die Mobs solange mit einer Leine geschlagen werden, bis diese in ein Pet umgewandelt werden.


{.compact}
Mob-Typ         | Anforderung       | HP-Grenze | Chance    | mcMMO-Level   | Skill         | Skill         | Skill         | Skill
:---:           | :---:             | ---       | ---       | ---           | ---           | ---           | ---           | ---        
Allay           | -                 | 20%       | 30%       | 400           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Armadillo       | -                 | 30%       | 50%       | 200           | Zähmen        | Kräuterkunde  | -             | -
Axolotl         | -                 | 30%       | 50%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Bat             | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Bee             | -                 | 40%       | 65%       | 200           | Zähmen        | Graben        | Akrobatik     | -
Blaze           | -                 | 30%       | 50%       | 300           | Zähmen        | Alchemie      | Akrobatik     | Schwert
Bogged          | -                 | 30%       | 50%       | 300           | Zähmen        | Bogenschießen | -             | -
Breeze          | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Schwert       | -
Camel           | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Cat             | Gezähmt           | 40%       | 65%       | 200           | Zähmen        | Kräuterkunde  | -             | -
Cave Spider     | -                 | 40%       | 65%       | 200           | Zähmen        | Graben        | Schwert       | Aktobatik
Chicken         | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Cod             | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Cow             | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Creaking        | -                 | 10%       | 20%       | 500           | Zähmen        | Holzfällen    | -             | -
Creeper         | -                 | 50%       | 80%       | 100           | Zähmen        | Schwert       | -             | -
Dolphin         | -                 | 20%       | 30%       | 400           | Zähmen        | Angeln        | Kräuterkunde  | -
Donkey          | Gezähmt           | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Drowned         | -                 | 50%       | 65%       | 200           | Tridents      | Zähmen        | Schwert       | Angeln
Elder Guardian  | -                 | 20%       | 30%       | 400           | Tridents      | Zähmen        | -             | -
Enderman        | -                 | 40%       | 65%       | 200           | Zähmen        | Schwert       | -             | -
Endermite       | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwert       | -
Evoker          | -                 | 20%       | 30%       | 400           | Zähmen        | Kräuterkunde  | Alchemie      | -
Fox             | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Frog            | -                 | 40%       | 65%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Ghast           | -                 | 20%       | 30%       | 400           | Zähmen        | Schwert       | Alchemie      | -
Glow Squid      | -                 | 40%       | 65%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Goat            | -                 | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Guardian        | -                 | 40%       | 65%       | 200           | Tridents      | Zähmen        | -             | -
Hoglin          | -                 | 30%       | 50%       | 300           | Zähmen        | Schwert       | Alchemie      | Akrobatik
Horse           | Gezähmt           | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Husk            | -                 | 30%       | 50%       | 300           | Zähmen        | Schwert       | -             | -
Iron Golem      | Erschaffen        | 20%       | 30%       | 400           | Zähmen        | Reparatur     | -             | -
Llama           | Gezähmt           | 50%       | 80%       | 100           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Magma Cube      | -                 | 40%       | 65%       | 200           | Zähmen        | Schwert       | Alchemie      | -
Mooshroom       | -                 | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Mule            | Gezähmt           | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Ocelot          | -                 | 30%       | 50%       | 300           | Zähmen        | Kräuterkunde  | -             | -
Panda           | -                 | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Parrot          | Gezähmt           | 30%       | 50%       | 200           | Akrobatik     | Kräuterkunde  | -             | -
Phantom         | -                 | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Schwert       | -
Pig             | -                 | 60%       | 100%      | -             | -             | -             | -             | - 
Piglin          | -                 | 30%       | 50%       | 300           | Zähmen        | Schwert       | Alchemie      | -
Piglin Brute    | -                 | 20%       | 30%       | 400           | Zähmen        | Schwert       | Alchemie      | -
Pillager        | -                 | 30%       | 50%       | 200           | Zähmen        | Kräuterkunde  | Faustkampf    | -
Polar Bear      | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Pufferfish      | -                 | 30%       | 50%       | 300           | Zähmen        | Angeln        | Kräuterkunde  | -
Rabbit          | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Ravanger        | -                 | 10%       | 20%       | 500           | Zähmen        | Schwert       | Aktobatik     | -
Salmon          | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Sheep           | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Silverfish      | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwert       | -
Skeleton        | -                 | 50%       | 80%       | 100           | Zähmen        | Bogenschießen | -             | -
Skeleton Horse  | Gezähmt           | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | -             | -
Slime           | -                 | 50%       | 80%       | 100           | Zähmen        | Schwert       | Akrobatik     | -
Sniffer         | -                 | 20%       | 30%       | 400           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Snow Golem      | Erschaffen        | 30%       | 50%       | 200           | Zähmen        | Reparatur     | -             | -
Spider          | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwert       | Akrobatik
Squid           | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Stray           | -                 | 30%       | 50%       | 300           | Zähmen        | Bogenschießen | -             | -
Strider         | -                 | 30%       | 50%       | 200           | Zähmen        | Schwert       | Alchemie      | Akrobatik
Tadpole         | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Trader Llama    | Gezähmt           | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Tropical Fish   | -                 | 30%       | 50%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Turtle          | -                 | 30%       | 50%       | 200           | Zähmen        | Angeln        | Akrobatik     | -
Vex             | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Schwert       | -
Villager        | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Vindicator      | -                 | 10%       | 20%       | 500           | Zähmen        | Kräuterkunde  | Faustkampf    | -
Wandering Trader| -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Warden          | -                 | 10%       | 20%       | 500           | Zähmen        | Holzfällen    | -             | -
Witch           | -                 | 30%       | 50%       | 300           | Zähmen        | Kräuterkunde  | Alchemie      | -
Wither          | -                 | 10%       | 20%       | 500           | Zähmen        | Schwert       | Alchemie      | -
Wither Skeleton | -                 | 20%       | 30%       | 400           | Zähmen        | Schwert       | Alchemie      | -
Wolf            | Gezähmt           | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Zoglin          | -                 | 20%       | 30%       | 400           | Zähmen        | Schwert       | Alchemie      | -
Zombie          | -                 | 50%       | 80%       | 100           | Zähmen        | Schwert       | -             | -
Zombie Horse    | Gezähmt           | 20%       | 30%       | 400           | Zähmen        | Akrobatik     | -             | -
Zombie Villager | -                 | 30%       | 50%       | 200           | Zähmen        | Schwert       | -             | -
Zombified Piglin| -                 | 30%       | 50%       | 200           | Zähmen        | Schwert       | Alchemie      | -

Folgende Tiere sind nicht einfangbar:
- Illusioner
- Dragon
- Shulker

Folgende Tiere verschwinden beim Freilassen:
- Ghast
- Wandering Trader
- Warden
- Wither
- Wither Skeleton


Gefangene Mobs können eingelagert, getauscht, gehandelt oder auch wieder freigelassen werden. Weitere Infos dazu findest du unter [Befehle](#befehle).

---

## Pet leveln
Um ein Pet zu leveln, muss dieses aktiv mit dir mitlaufen, während du Monster tötest. Das Pet erhält hierbei mehr Erfahrung, sollte es Mobs selbst töten.

Dabei sammelt dein Pets in den verschiedenen Welten unterschiedlich schnell Erfahrung:
- Industriewelt: 50%
- Bauwelt: 100%
- Farmwelt: 125%

Jede Klasse kann bis Level 80 aufsteigen.

---
## Stärke-Kategorien

Die Stärke der verschiedenen Mobs werden in fünf Kategorien (S0-schwach bis S5-stark) gegliedert.
Mobs, welche in der gleichen Zeile gelistet sind bauen in gewissem Maße aufeinander auf.

{.compact}
S0              | S1                | S2                            | S3                | S4                | S5            
:---:           | :---:             | ---                           | ---               | ---               | ---
                |                   |                               |                   | Witherskelett     | Wither
                |                   |                               | Böe               |                   |
                |                   | Schreiter                     |                   |                   |
                |                   |                               | Lohe              | Ghast             |
                |                   |                               | Hoglin            | Zoglin            |
                |                   |                               | Plagegeist        | Hilfsgeist        |
                | Endermite         | Enderman                      |                   |                   |
                |                   | Ertrunkener                   |                   |                   |
                | Zombie            | Zombifizierter Dorfbewohner   | Wüstenzombie      |                   |
                | Creeper           |                               |                   |                   |
                |                   |                               | Sumpfskelett      |                   | Knarz
                | Schleim           | Magmawürfel                   |                   |                   |
                | Spinne            | Höhlenspinne                  |                   |                   |
                | Skelett           |                               | Eiswanderer       |                   |
                |                   |                               | Eisbär            |                   |
                |                   | Wächter                       |                   | Großwächter       |
                |                   | Phantom                       |                   |                   |
                | Silberfisch       |                               |                   |                   |
                |                   | Schneemann                    |                   | Golem             | Wärter
Schaf           |                   |                               |                   |                   |
Schwein         |                   | Zombifizierter Piglin         | Piglin            | Piglin Barbar     |
Kuh             |                   | Pilzkuh                       |                   |                   | Verwüster
Huhn            |                   | Papagei                       |                   |                   |
Dorfbewohner    | Händler           | Plünderer                     | Hexe              | Magier            | Diener
                |                   | Schildkröte                   |                   | Schnüffler        |
                |                   | Katze                         | Ozelot            |                   |
                | Lama              | Händlerlama                   | Kamel             |                   |
                |                   | Axolotl                       |                   |                   |
                |                   | Biene                         |                   |                   |
                | Kabeljau, Lachs   | Tropischer Fisch              | Kugelfisch        | Delfin            |
                | Esel, Maultier    | Pferd                         | Skelettpferd      | Zombiepferd       |
                | Tintenfisch       | Leuchttintenfisch             |                   |                   |
                |                   | Panda                         |                   |                   |
                | Kaulquappe        | Frosch                        |                   |                   |
                | Fledermaus        |                               |                   |                   |
                | Hase              |                               |                   |                   |
                |                   |                               | Wolf              |                   |
                |                   | Ziege                         |                   |                   |
                | Fuchs             |                               |                   |                   |
                |                   | Gürteltier                    |                   |                   |

---
## Klassen
Klassen verändern die Stärke (bzw. Fähigkeiten) eines Haustiers. Die Art der Bewegung, Erscheinung oder das Level-System des Haustiers ändert sich hierbei nicht. Jede Petklasse bietet unterschiedliche Fähigkeiten.

Steigt das Level deines Haustiers, so können unterschiedliche Fähigkeiten gesteigert werden:
- Schaden
- Maximales Leben
- Lebensregeneration über Zeit
- Leuchtfeuer-Effekte
- Reitgeschwindigkeit/Flugreichweite
- Vergrößertes Inventar

Viele Fähigkeiten und Zustände werden erst im späteren Verlauf freigeschaltet.

Eine Übersicht über die verschiedenen Petklassen kann [hier](https://docs.google.com/spreadsheets/d/1-OIfTc-EogHypyZgFHk6HFBQd_LuoNDw50PtR9IuBOI/edit?usp=sharing) gefunden werden.

---

## Zustände
Ein Pet kann mit `/petbehaviour` in verschiedene Zustände versetzt werden:

{.compact}
Zustand     | Beschreibung
:---:       | ---
Friendly    | Dein Pet greift keine Mobs an, egal ob es selbst angegriffen wird.
Normal      | Dein Pet greift nur an, wenn du/es von einem Gegner getroffen wirst/wird.
Aggressive  | Dein Pet greift alles im Umkreis von 15 Blöcken an (Mobs sowie Spieler).
Farm        | Dein Pet greift alle Mobs im Umkreis von 15 Blöcken um dich an.
Raid        | Dein Pet greift nur feindliche Mobs an (Zombies, Skelette, etc) und keine Pets anderer Personen oder Villager.
Duel        | Dein Pet greift Pets anderer Spieler an, deren Zustand auch auf "duel" gestellt ist (im Umkreis von 5 Blöcken).

---

## Zusätzliche Informationen
### Rüstung & Waffen anziehen
Durch das Schleichen + Rechtsklicken mit Waffen & Rüstungen kann manchen Pets Equipment angelegt werden. Diese sind rein optisch und dienen dazu, deine Pets interessanter aussehen zu lassen.

Das Equipment kann entfernt werden, indem du mit deinem Pet via Schleichen + Rechtsklick mit einer Schere interagierst.

---

## Befehle
`/petinfo`\
Zeigt Informationen zum aktiven Pet.

`/petname <neuer name>`\
Benennt das aktive Pet um.

`/petlist`\
Listet alle deine Pets auf.

`/petswitch`\
Ermöglicht das Wechseln oder Rufen von Pets.

`/petstore`\
Schickt dein aktives Pet in einen virtuellen Stall.

`/petinventory`\
Öffnet das Pet-Inventar.

`/petcall`\
Ruft das aktive Pet zu dir.

`/petsendaway`\
Schickt das Pet weg. Es kann weiterhin durch /petcall gerufen werden.

`/petpickup`\
Aktiviert/Deaktiviert das Aufheben von Items durch das Pet.

`/petrelease`\
Lässt das aktive Pet frei. Wardens und Witherkelette verschwinden beim Verwenden von /petrelease. Es gibt dann keine Möglichkeit, das freigelassene Pet erneut zu zähmen.

`/petrespawn [pay/show/auto]`\
Belebt ein totes Pet wieder.

`/pettrade [accept/reject/cancel/spielername]`\
Hiermit kann ein aktives Pet verkauft/gekauft werden. Wird der Betrag leer gelassen, ist es ein Geschenk.

`/petskill`\
Zeigt die Fähigkeiten deines aktiven Pets.

`/petchooseskilltree oder /pcst`\
Hiermit kann der Skill deines aktiven Pets ausgewählt oder gewechselt werden.

`/petbehavior oder /petbehaviour`\
Ändert den Zustand deines aktiven Pets.

`/petbeacon`\
Hiermit können Beaconeffekte ausgewählt werden, die das Pet je nach Skilltree und Level ausstrahlen kann.
