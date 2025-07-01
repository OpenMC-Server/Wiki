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

!!!warning Bereich in Arbeit
Die Details zu den Mobs und ihren Stärke-Kategorien sind zurzeit noch in Arbeit.
Zeitweise sind die Infos [hier](https://docs.google.com/spreadsheets/d/1-OIfTc-EogHypyZgFHk6HFBQd_LuoNDw50PtR9IuBOI/edit?gid=0#gid=0) zu entnehmen.
!!!

+++ S0
- **Dorfbewohner**
  - Grundleben: 25 (max. 70)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Regeneration II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Huhn**
  - Grundleben: 30 (max. 40)
  - Kampftyp: Nahkampf/Fernkampf
  - Schaden: 0 (max. 8)
  - Leuchtfeuereffekte: Regeneration II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.43
  - Nahrung: Weizensamen, Kürbissamen, Melonensamen, Rote-Beete-Samen, Fackelliliensamen, Süßbeere, Ei
- **Kuh**
  - Grundleben: 35 (max. 75)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Regeneration II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Melonenschreibe
- **Schaf**
  - Grundleben: 35 (max. 75)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Regeneration II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass
- **Schwein**
  - Grundleben: 35 (max. 75)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Regeneration II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Melonenschreibe, Brot, Süßbeere, Leuchtbeere 


+++ S1
- **Creeper**
  - Grundleben: 30 (max. 45)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 18)
  - Leuchtfeuereffekte: Resistenz II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Fire
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Schwarzpulver, Feuerstein, TnT
- **Endermite**
  - Grundleben: 25 (max. 66)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Geschwindigkeit I, Regeneration I, Absorption II, Nachtsicht
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Fire
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.28
  - Nahrung: Chorusfrucht, Chorusblüte, Spinnenauge, Obsidian, Weinendes Obsidian
- **Esel**
  - Grundleben: 35 (max. 65)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Geschwindigkeit II, Stärke I, Regeneration I
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass
- **Fledermaus**
  - Grundleben: 15 (max. 40)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Regeneration III, Geschwindigkeit I
  - Inventar: 2 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Spinnenauge, Honigwabe, Süßbeere, Leuchtbeere
- **Fuchs**
  - Grundleben: 20 (max. 57)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Stärke II, Geschwindigkeit I, Resistenz II
  - Inventar: 2 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Süßbeere, Leuchtbeere, Rohes Hünchen, Rohes Kaninchen
- **Hase**
  - Grundleben: 20 (max. 63)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Sprungkraft II, Geschwindigkeit III
  - Inventar: ! Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Karotte, Apfel, Rote Beete, Süßbeere, Brot, Leuchtbeere
- **Kabeljau**
- **Kaulquappe**
- **Papagei**
- **Händler**
- **Lachs**
- **Lama**
- **Maultier**
- **Schleim**
- **Silberfisch**
- **Skelett**
- **Spinne**
- **Tintenfisch**
- **Zombie**

+++ S2
- **Axolotl**
  - Grundleben: 15 (max. 62)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Geschwindigkeit II, Regeneration II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Slow
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch, Pufferfisch
- **Biene**
  - Grundleben: 15 (max. 56)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 12)
  - Leuchtfeuereffekte: Geschwindigkeit II, Resistenz II, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Ride/Fly
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Honigflasche, Blumen
- **Enderman**
  - Grundleben: 30 (max. 75)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 19.5)
  - Leuchtfeuereffekte: Geschwindigkeit I, Regeneration I, Absorption II, Nachtsicht
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback,Thorns
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.23
  - Nahrung: Chorusfrucht, Chorusblüte, Obsidian, Weinendes Obsidian
- **Ertrunkener**
  - Grundleben: 35 (max. 77)
  - Kampftyp: Nahkampf/Fernkampf
  - Schaden: 0 (max. 20.2)
  - Leuchtfeuereffekte: Absorption I, Resistenz I, Stärke II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Verrotetes Fleisch, Kabeljau, Lachs, Tropischer Fisch
- **Frosch**
  - Grundleben: 15 (max. 66)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Absorption III
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Poison, Slow
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Spinnenauge, Pahntommembrane, Schleimball, Magmacreme
- **Gürteltier**
  - Grundleben: 20 (max. 70)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Absorption I, Resistenz I
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback, Slow, Shield
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Spinnenauge, Apfel, Süßbeere, Leuchtbeere, Brauner Pilz
- **Händlerlama**
- **Höhlenspinne**
- **Katze**
- **Leuchttintenfisch**
- **Magmawürfel**
- **Panda**
- **Pferd**
- **Phantom**
- **Pilzkuh**
- **Plünderer**
- **Schildkröte**
- **Schneemann**
- **Schreiter**
- **Tropischer Fisch**
- **Wächter**
- **Ziege**
- **Zombifizierter Dorfbewohner**
- **Zombifizierter Piglin**

+++ S3
- **Böe**
- **Eisbär**
- **Eiswanderer**
- **Hexe**
- **Hoglin**
- **Kamel**
- **Kugelfisch**
- **Lohe**
- **Ozelot**
- **Piglin**
- **Plagegeist**
- **Skelettpferd**
- **Skumpskelett**
- **Wolf**
- **Wüstenzombie**

+++ S4
- **Delfin**
- **Ghast**
- **Golem**
- **Großwächter**
- **Hilfsgeist**
  - Grundleben: 15 (max. 55)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Geschinwdigkeit II, Stärker II, Resistenz I, Regeneration I, Abbaugeschwindigkeit II
  - Inventar: 3 Reihen
  - Fähigkeiten: Ride/Fly
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Amethystscherbe, Obsidian, Smaragdblock
- **Magier**
- **Piglin Barbar**
- **Schnüffler**
- **Witherskelett**
- **Zoglin**
- **Zombiepferd**

+++ S5
- **Diener**
  - Grundleben: 40 (max. 113)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 18)
  - Leuchtfeuereffekte: Resistenz II, Stärke II
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback, Slow, Thorn
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.32
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Knarz**
  - Grundleben: 50 (max. 148)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6.6)
  - Leuchtfeuereffekte: Regeneration III, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Poison, Slow, Thorns
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.2
  - Nahrung: Honigwabe, Harzklumpen
- **Verwüster**
  - Grundleben: 45 (max. 124)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 12)
  - Leuchtfeuereffekte: Regeneration III, Stärke II
  - Inventar: 4 Reihen
  - Fähigkeiten: Fly/Ride, Stomp
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.33
  - Nahrung: Rote Beete, Karotten, Weizen, Blätter 
- **Wärter**
  - Grundleben: 50 (max. 155)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 25)
  - Leuchtfeuereffekte: Absorption III
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Shield
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.2
  - Nahrung: Leuchtbeere, Antiker Schrott, Sculk, Sculk-Kreischer
- **Wither**
  - Grundleben: 55 (max. 113)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 20)
  - Leuchtfeuereffekte: Feuerresistenz, Stärke III, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Thorns, Wither
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Seelensand, Seelenerde, Kohle, Holzkohle, Feuerstein, Scharzpulver
  - **Verschwindet beim Freilassen**
+++

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
