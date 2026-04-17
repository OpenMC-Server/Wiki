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
Blaze           | -                 | 30%       | 50%       | 300           | Zähmen        | Alchemie      | Akrobatik     | Schwertkampf
Bogged          | -                 | 30%       | 50%       | 300           | Zähmen        | Bogenschießen | -             | -
Breeze          | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Schwertkampf       | -
Camel           | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Cat             | -                 | 40%       | 65%       | 200           | Zähmen        | Kräuterkunde  | -             | -
Cave Spider     | -                 | 40%       | 65%       | 200           | Zähmen        | Graben        | Schwertkampf       | Aktobatik
Chicken         | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Cod             | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Cow             | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Creaking        | Herz abbauen      | -         | 100%      | 500           | Zähmen        | Holzfällen    | -             | -
Creeper         | -                 | 50%       | 80%       | 100           | Zähmen        | Schwertkampf  | -             | -
Dolphin         | -                 | 20%       | 30%       | 400           | Zähmen        | Angeln        | Kräuterkunde  | -
Donkey          | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Drowned         | -                 | 50%       | 65%       | 200           | Tridents      | Zähmen        | Schwertkampf       | Angeln
Elder Guardian  | -                 | 20%       | 30%       | 400           | Tridents      | Zähmen        | -             | -
Enderman        | -                 | 40%       | 65%       | 200           | Zähmen        | Schwertkampf  | -             | -
Endermite       | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwertkampf  | -
Evoker          | -                 | 20%       | 30%       | 400           | Zähmen        | Kräuterkunde  | Alchemie      | -
Fox             | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Frog            | -                 | 40%       | 65%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Ghast           | -                 | 20%       | 30%       | 400           | Zähmen        | Schwertkampf  | Alchemie      | -
Glow Squid      | -                 | 40%       | 65%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Goat            | -                 | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Guardian        | -                 | 40%       | 65%       | 200           | Tridents      | Zähmen        | -             | -
Hoglin          | -                 | 30%       | 50%       | 300           | Zähmen        | Schwertkampf  | Alchemie      | Akrobatik
Horse           | -                 | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Husk            | -                 | 30%       | 50%       | 300           | Zähmen        | Schwertkampf  | -             | -
Iron Golem      | Erschaffen        | 20%       | 30%       | 400           | Zähmen        | Reparatur     | -             | -
Llama           | -                 | 50%       | 80%       | 100           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Magma Cube      | -                 | 40%       | 65%       | 200           | Zähmen        | Schwertkampf  | Alchemie      | -
Mooshroom       | -                 | 40%       | 65%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Mule            | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | Akrobatik     | -
Ocelot          | -                 | 30%       | 50%       | 300           | Zähmen        | Kräuterkunde  | -             | -
Panda           | -                 | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Parrot          | -                 | 30%       | 50%       | 200           | Akrobatik     | Kräuterkunde  | -             | -
Phantom         | -                 | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Schwertkampf  | -
Pig             | -                 | 60%       | 100%      | -             | -             | -             | -             | - 
Piglin          | -                 | 30%       | 50%       | 300           | Zähmen        | Schwertkampf  | Alchemie      | -
Piglin Brute    | -                 | 20%       | 30%       | 400           | Zähmen        | Schwertkampf  | Alchemie      | -
Pillager        | -                 | 30%       | 50%       | 200           | Zähmen        | Kräuterkunde  | Faustkampf    | -
Polar Bear      | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Pufferfish      | -                 | 30%       | 50%       | 300           | Zähmen        | Angeln        | Kräuterkunde  | -
Rabbit          | -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Ravanger        | -                 | 10%       | 20%       | 500           | Zähmen        | Schwertkampf  | Aktobatik     | -
Salmon          | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Sheep           | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Silverfish      | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwertkampf  | -
Skeleton        | -                 | 50%       | 80%       | 100           | Zähmen        | Bogenschießen | -             | -
Skeleton Horse  | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | -             | -
Slime           | -                 | 50%       | 80%       | 100           | Zähmen        | Schwertkampf  | Akrobatik     | -
Sniffer         | -                 | 20%       | 30%       | 400           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Snow Golem      | Erschaffen        | 30%       | 50%       | 200           | Zähmen        | Reparatur     | -             | -
Spider          | -                 | 50%       | 80%       | 100           | Zähmen        | Graben        | Schwertkampf  | Akrobatik
Squid           | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Stray           | -                 | 30%       | 50%       | 300           | Zähmen        | Bogenschießen | -             | -
Strider         | -                 | 30%       | 50%       | 200           | Zähmen        | Schwertkampf  | Alchemie      | Akrobatik
Tadpole         | -                 | 50%       | 80%       | 100           | Zähmen        | Angeln        | Kräuterkunde  | -
Trader Llama    | -                 | 30%       | 50%       | 200           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Tropical Fish   | -                 | 30%       | 50%       | 200           | Zähmen        | Angeln        | Kräuterkunde  | -
Turtle          | -                 | 30%       | 50%       | 200           | Zähmen        | Angeln        | Akrobatik     | -
Vex             | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Schwertkampf  | -
Villager        | -                 | 60%       | 100%      | -             | -             | -             | -             | -
Vindicator      | -                 | 10%       | 20%       | 500           | Zähmen        | Kräuterkunde  | Faustkampf    | -
Wandering Trader| -                 | 50%       | 80%       | 100           | Zähmen        | Kräuterkunde  | -             | -
Warden          | -                 | 10%       | 20%       | 500           | Zähmen        | Holzfällen    | -             | -
Witch           | -                 | 30%       | 50%       | 300           | Zähmen        | Kräuterkunde  | Alchemie      | -
Wither          | -                 | 10%       | 20%       | 500           | Zähmen        | Schwertkampf  | Alchemie      | -
Wither Skeleton | -                 | 20%       | 30%       | 400           | Zähmen        | Schwertkampf  | Alchemie      | -
Wolf            | -                 | 30%       | 50%       | 300           | Zähmen        | Akrobatik     | Kräuterkunde  | -
Zoglin          | -                 | 20%       | 30%       | 400           | Zähmen        | Schwertkampf  | Alchemie      | -
Zombie          | -                 | 50%       | 80%       | 100           | Zähmen        | Schwertkampf  | -             | -
Zombie Horse    | -                 | 20%       | 30%       | 400           | Zähmen        | Akrobatik     | -             | -
Zombie Villager | -                 | 30%       | 50%       | 200           | Zähmen        | Schwertkampf  | -             | -
Zombified Piglin| -                 | 30%       | 50%       | 200           | Zähmen        | Schwertkampf  | Alchemie      | -

Folgende Tiere sind nicht einfangbar:
- Illusioner
- Dragon
- Shulker
- Temporär: Nautilus, Zombie Nautilus, Parched, Husk Camel, Happy Ghast

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

[!button variant="primary" text="Alle Stärkekategorien einsehen"](https://docs.google.com/spreadsheets/d/1-OIfTc-EogHypyZgFHk6HFBQd_LuoNDw50PtR9IuBOI/edit?usp=sharing)

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
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Karotte, Apfel, Rote Beete, Süßbeere, Brot, Leuchtbeere
- **Kabeljau**
  - Grundleben: 15 (max. 60)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Absorption III, Geschwindigkeit II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Getrockneter Seetang, Seetang, Seegras, Seegurke, Karotte, Kabeljau, Tropischer Fisch, Laschs
- **Kaulquappe**
  - Grundleben: 15 (max. 58)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Absorption III
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Schleimball, Seegras, Seegurke, Seetang
- **Papagei**
  - Grundleben: 15 (max. 65)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Geschwindigkeit II, Regeneration II
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.35
  - Nahrung: Weizensamen, Kürbissamen, Melonensamen, Rote-Beete-Samen, Fackelliliensamen, Süßbeere, Leuchtbeere, Apfel, Melonenscheibe
- **Wandernder Händler**
  - Grundleben: 25 (max. 63)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Resistenz II, Stärke II, Unsichtbarkeit
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Lachs**
  - Grundleben: 15 (max. 60)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Absorption III, Geschwindigkeit II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Getrockneter Seetang, Seetang, Seegras, Seegurke
- **Lama**
  - Grundleben: 35 (max. 59)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Absorption II, Regenration II
  - Inventar: 2 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Melonenscheibe
- **Maultier**
  - Grundleben: 35 (max. 65)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Geschwindigkeit II, Stärke I, Regenration I
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass
- **Schleim**
  - Grundleben: 45 (max. 76)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 3.9)
  - Leuchtfeuereffekte: Resistenz II, Regeneration II
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.33
  - Nahrung: Schleimball, Honigwabe, Spinnenauge, Glitzernde Melonenscheibe
- **Silberfisch**
  - Grundleben: 25 (max. 59)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Regeneration I, Geschwindigkeit I, Absorption II, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Poison
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Spinnenauge, Zucker, Eisenklumpen, Steinziegel
- **Skelett**
  - Grundleben: 15 (max. 47)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 20)
  - Leuchtfeuereffekte: Regeneration III, Stärke I
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Knochenmehl, Milcheimer, Goldklumpen
- **Spinne**
  - Grundleben: 40 (max. 73)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Geschwindigkeit II, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Spinnenauge, Phantommembrane, Brauner Pilz, Roter Pilz, Rohe Hünchen
- **Tintenfisch**
  - Grundleben: 15 (max. 45)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Resistenz II, Regeneration II, Geschwindigkeit II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Shield
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch
- **Zombie**
  - Grundleben: 30 (max. 80)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Stärke II, Regeneration II, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Steak, Gebratenes Scheinefleisch, Rohes Hammelfleisch, Rohes Hünchen, Rohes Kaninchen, Verrottetes Fleisch

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
  - Grundleben: 35 (max. 60)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Absorption II, Regeneration II
  - Inventar: 4 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Melonenscheibe
- **Höhlenspinne**
  - Grundleben: 40 (max. 73)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Fly/Ride, Geschwindigkeit II, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Spinnenauge, Phantommembrane, Brauner Pilz, Roter Pilz, Rohe Hünchen
- **Katze**
  - Grundleben: 20 (max. 69)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 13.2)
  - Leuchtfeuereffekte: Geschwindigkeit II, Sprungkraft I, Stärke I, Resistenz II
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch, Steak, Gebratenes Schweinefleisch, Rohes Hammelfleisch
- **Leuchttintenfisch**
  - Grundleben: 15 (max. 60)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Resistenz II, Regeneration II, Geschwindigkeit II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Shield
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Leuchtbeere, Kabeljau, Lachs, Leuchtsteinstaub
- **Magmawürfel**
  - Grundleben: 55 (max. 86)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 8.4)
  - Leuchtfeuereffekte: Resistenz II, Regeneration II, Feuerresistenz
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride, Fire, Knockback
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Magmacreme, Honigwabe, Spinnenauge, Glitzernde Honigmelone
- **Panda**
  - Grundleben: 35 (max. 85)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Regeneration II
  - Inventar: 2 Reihen
  - Fähigkeiten: Fly/Ride, Stomp
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Bambus, Zuckerrohr
- **Pferd**
  - Grundleben: 35 (max. 70)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Geschwindigkeit II, Stärke I, Regeneration I
  - Inventar: 5 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Melonenschreibe
- **Phantom**
  - Grundleben: 25 (max. 45)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 13.5)
  - Leuchtfeuereffekte: Geschwindigkeit II
  - Inventar: 2 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Spinnenauge, Verrottetes Fleisch
- **Pilzkuh**
  - Grundleben: 35 (max. 77)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6)
  - Leuchtfeuereffekte: Regeneration III, Stärke II
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Brauner Pilz, Roter Pilz, Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass, Myzelium
- **Plünderer**
  - Grundleben: 40 (max. 86)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Resistenz II, Stärke II, Geschwindigkeit I
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.32
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Schildkröte**
  - Grundleben: 30 (max. 90)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6.6)
  - Leuchtfeuereffekte: Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Fly/Ride, Shield
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Getrockneter Seetang, Seetang, Seegrass, Seegurke, Melonenscheibe, Kürbis, Karotte, Süßbeere, Leuchtbeere
- **Schneemann**
  - Grundleben: 60 (max. 124)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 0.5)
  - Leuchtfeuereffekte: Absorption III
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.2
  - Nahrung: Schneeball, Karotte, Kürbis, Packeis
- **Schreiter**
  - Grundleben: 70 (max. 130)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9.6)
  - Leuchtfeuereffekte: Resistenz II, Absorption II, Feuerresistenz
  - Inventar: 1 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.33
  - Nahrung: Wirrwurzeln, Wirrpilz, Netherwarzen, Karmesinwurzeln, Karmesinpilz
- **Tropischer Fisch**
  - Grundleben: 15 (max. 63)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Absorption III, Geschwindigkeit II, Wasseratmung
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Getrockneter Seetang, Seetang, Seegras, Seegurke
- **Wächter**
  - Grundleben: 35 (max. 77)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 13)
  - Leuchtfeuereffekte: Absorption II, Resistenz II, Wasseratmung
  - Fähigkeiten: Lightning, Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch
- **Ziege**
  - Grundleben: 35 (max. 74)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.2)
  - Leuchtfeuereffekte: Sprungkraft II, Resistenz II
  - Inventar: 2 Reihen
  - Fähigkeiten: Fly/Ride, Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Weizen, Karotte, Apfel, Rote Beete, Süßbeere, Getrockneter Seetang, Seetang, Seegrass
- **Zombifizierter Dorfbewohner**
  - Grundleben: 30 (max. 90)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Regeneration II, Stärke II, Resistenz II
  - Inventar: 2 Reihen
  - Fähigkeiten: Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Steak, Gebratenes Scheinefleisch, Rohes Hammelfleisch, Rohes Hünchen, Rohes Kaninchen, Verrottetes Fleisch
- **Zombifizierter Piglin**
  - Grundleben: 55 (max. 115)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 12)
  - Leuchtfeuereffekte: Regeneration II, Stärke II, Feuerresistenz
  - Inventar: 1 Reihen
  - Fähigkeiten: N/A
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Wirrwurzeln, Wirrpilz, Netherwarzen, Karmesinwurzeln, Karmesinpilz, Steak, Rohes Scheinefleisch, Rohes Hammelfleisch, Verrottetes Fleisch

+++ S3
- **Böe**
  - Grundleben: 25 (max. 54)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Geschwindigkeit II, Sprungkraft II
  - Inventar: 1 Reihen
  - Fähigkeiten: Slow, Lightning, Knockback
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Windkugel, Feder
- **Eisbär**
  - Grundleben: 35 (max. 96)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Stärke II, Absorption II
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch, Steak, Rohes Schweinefleisch, Rohes Hammelfleisch, Rohes Hühnchen, Rohes Kaninchen
- **Eiswanderer**
  - Grundleben: 15 (max. 59)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 25)
  - Leuchtfeuereffekte: Regeneration III, Stärke I
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Knochenmehl, Milcheimer, Goldklumpen
- **Hexe**
  - Grundleben: 35 (max. 73)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 25)
  - Leuchtfeuereffekte: Resistenz II, Stärke III, Geschwindigkeit I
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback, Lightning
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Hoglin**
  - Grundleben: 70 (max. 135)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Regeneration II, Feuerresistenz
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride, Stomp
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.33
  - Nahrung: Wirrwurzeln, Netherwarzen, Karmesinpilz, Rohes Scheinefleisch, Gebratenes Scheinefleisch
- **Kamel**
  - Grundleben: 35 (max. 70)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Absorption II, Regeneration II
  - Inventar: 5 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.38
  - Nahrung: Sand, Cactus, Toter Busch, Apfel, Karotte, Rote Beete
- **Kugelfisch**
  - Grundleben: 15 (max. 75)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Absorption III, Geschwindigkeit II, Wasseratmung
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback, Poison
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch, Schwamm
- **Lohe**
  - Grundleben: 50 (max. 97)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Stärke III, Feuerresistenz
  - Inventar: 1 Reihen
  - Fähigkeiten: Fire
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Schwarzpulver, Kohle, Holzkohle, Feuerstein
- **Ozelot**
  - Grundleben: 20 (max. 76)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 16.2)
  - Leuchtfeuereffekte: Geschwindigkeit II, Sprungkraft I, Stärke I, Resistenz II, Nachtsicht
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch, Steak, Rohes Schweinefleisch, Rohes Hammelfleisch, Rohes Hühnchen, Rohes Kaninchen
- **Piglin**
  - Grundleben: 55 (max. 135)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 13.5)
  - Leuchtfeuereffekte: Regeneration II, Stärke II, Feuerresistenz
  - Inventar: 2 Reihen
  - Fähigkeiten: Fire
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Wirrwurzeln, Wirrpilz, Netherwarzen, Karmesinwurzeln, Karmesinpilz, Rohes Scheinefleisch, Gebratenes Scheinefleisch
- **Plagegeist**
  - Grundleben: 25 (max. 62)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Geschinwdigkeit II, Stärke III, Resistenz I, Regeneration I
  - Inventar: 1 Reihen
  - Fähigkeiten: Ride/Fly, Lightning
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.3
  - Nahrung: Obsidian, Weinendes Obsidian, Enderperle
- **Skelettpferd**
  - Grundleben: 35 (max. 80)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Geschwindigkeit II, Stärke I, Regeneration I
  - Inventar: 5 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Knochenmehl, Milcheimer, Goldklumpen
- **Sumpfskelett**
  - Grundleben: 15 (max. 59)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Regeneration III, Resistenz II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Poison, Thorns
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Brauner Pilz, Roter Pilz, Knochenmehl, Milcheimer, Goldklumpen
- **Wolf**
  - Grundleben: 20 (max. 80)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 12)
  - Leuchtfeuereffekte: Absorption II, Stärke II, Resistenz II, Regeneration II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Steak, Rohes Schweinefleisch, Rohes Hammelfleisch, Rohes Hühnchen, Rohes Kaninchen, Knochen
- **Wüstenzombie**
  - Grundleben: 30 (max. 100)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Stärke II, Regeneration II, Resistenz II
  - Inventar: 2 Reihen
  - Fähigkeiten: Poison, Slow
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Steak, Gebratenes Scheinefleisch, Rohes Hammelfleisch, Rohes Hünchen, Rohes Kaninchen, Verrottetes Fleisch

+++ S4
- **Delfin**
  - Grundleben: 15 (max. 75)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Absorption III, Geschwindigkeit II, Wasseratmung
  - Inventar: 1 Reihen
  - Fähigkeiten: Ride/Fly, Knockback
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.3
  - Nahrung: Kabeljau, Lachs, Tropischer Fisch
- **Ghast**
  - Grundleben: 55 (max. 102)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 24)
  - Leuchtfeuereffekte: Stärke III, Feuerresistenz
  - Inventar: 1 Reihen
  - Fähigkeiten: Fire
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Schwarzpulver, Feuerstein, Antiker Schrott, Quartz
  - **Verschwindet beim Freilassen**
- **Eisengolem**
  - Grundleben: 60 (max. 124)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 11.1)
  - Leuchtfeuereffekte: Absorption III
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Shield
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.2
  - Nahrung: Mohn, Roheisenblock
- **Großwächter**
  - Grundleben: 35 (max. 108)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 19.5)
  - Leuchtfeuereffekte: Geschwindigkeit I, Regeneration I, Absorption II, Nachtsicht
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Thorns
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.23
  - Nahrung: Chorusfrucht, Chorusblüte, Obsidian, Weinendes Obsidian
- **Hilfsgeist**
  - Grundleben: 15 (max. 55)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 15)
  - Leuchtfeuereffekte: Geschinwdigkeit II, Stärke II, Resistenz I, Regeneration I, Abbaugeschwindigkeit II
  - Inventar: 3 Reihen
  - Fähigkeiten: Ride/Fly
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.35
  - Nahrung: Amethystscherbe, Obsidian, Smaragdblock
- **Magier**
  - Grundleben: 20 (max. 35)
  - Kampftyp: Fernkampf
  - Schaden: 0 (max. 17.5)
  - Leuchtfeuereffekte: Resistenz II, Stärke II
  - Inventar: 2 Reihen
  - Fähigkeiten: Knockback, Lightning
  - Kann aufsammeln: Ja
  - Geschwindigkeit: 0.25
  - Nahrung: Apfel, Melonenscheibe, Süßbeere, Leuchtbeere, Chorusfrucht, Karotte, Gebackene Kartoffel, Rote Beete, Getrockneter Seetang, Steak, Gebratenes Schweinefleisch, Gebratenes Hühnchen, Gebratenes Kaninchen, Gebratenes Hammelfleisch, Gebratener Kabeljau, Gebratener Lachs, Brot, Kekse, Kuchen, Kürbiskuchen, Kaninchenragout, Rote-Beete-Suppe, Pilzsuppe, Honigflasche
- **Piglin Barbar**
  - Grundleben: 55 (max. 125)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 16.5)
  - Leuchtfeuereffekte: Regeneration II, Stärke II, Feuerresistenz
  - Inventar: 2 Reihen
  - Fähigkeiten: Fire
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Wirrwurzeln, Wirrpilz, Netherwarzen, Karmesinwurzeln, Karmesinpilz, Rohes Scheinefleisch, Gebratenes Scheinefleisch
- **Schnüffler**
  - Grundleben: 35 (max. 100)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 6.6)
  - Leuchtfeuereffekte: Absorption II
  - Inventar: 4 Reihen
  - Fähigkeiten: Fly/Ride, Shield, Stomp
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Weizensamen, Kürbissamen, Melonensamen, Rote-Beete-Samen, Fackelliliensamen, Süßbeere, Leuchtbeere, Apfel, Moosblock
- **Witherskelett**
  - Grundleben: 55 (max. 111)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 7.5)
  - Leuchtfeuereffekte: Feuerresistenz, Stärke II
  - Inventar: 1 Reihen
  - Fähigkeiten: Knockback, Thorns, Wither
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.2
  - Nahrung: Seelensand, Seelenerde, Kohle, Holzkohle, Feuerstein, Knochenmehl, Milcheimer
  - **Verschwindet beim Freilassen**
- **Zoglin**
  - Grundleben: 55 (max. 125)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 9)
  - Leuchtfeuereffekte: Regeneration II, Feuerresistenz, Resistenz II
  - Inventar: 3 Reihen
  - Fähigkeiten: Fly/Ride, Stomp
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.25
  - Nahrung: Wirrwurzeln, Netherwarzen, Karmesinpilz, Rohes Scheinefleisch, Gebratenes Scheinefleisch
- **Zombiepferd**
  - Grundleben: 35 (max. 105)
  - Kampftyp: Nahkampf
  - Schaden: 0 (max. 10.5)
  - Leuchtfeuereffekte: Geschwindigkeit II, Stärke I, Regeneration I
  - Inventar: 5 Reihen
  - Fähigkeiten: Fly/Ride
  - Kann aufsammeln: Nein
  - Geschwindigkeit: 0.38
  - Nahrung: Steak, Rohes Scheinefleisch, Rohes Hammelfleisch, Rohes Hühnchen, Rohes Kaninchen, Verrottetes Fleisch

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

[!button variant="primary" text="Alle Petklassen einsehen"](https://docs.google.com/spreadsheets/d/1-OIfTc-EogHypyZgFHk6HFBQd_LuoNDw50PtR9IuBOI/edit?usp=sharing)

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
