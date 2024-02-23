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

## Bridge-Schilder
Die Gate-Schilder ermöglichen es dir, mithilfe eines Schildes (oder zweien, sollte die Bridge von beiden Seiten aus verwendet werden können) eine Brücke zu erstellen, welche per Rechtsklick auf das zugehörige Schild ausgefahren oder eingefahren werden kann.

Um eine Bridge zu erstellen, ist es wichtig, dass der unter dem Schild gesetzte Block auch dem Material entspricht, mit dem die Brücke gebaut wird. Das Schild darüber erhält in der zweiten Zeile die Beschriftung `[Bridge]`, wodurch automatisch die Blockart in der ersten Zeile nun ausgefüllt werden sollte. Das gleiche kann bei Bedarf auf der anderen Seite der Brücke vorgenommen werden, sodass eine Breite von 5 Blöcken vorgegeben ist und eine Länge von maximal 30 Blöcken möglich ist.

Für eine Brücke können die unten angehangenen Blockarten verwendet werden:
<details>
    <summary>Klicke für eine Übersicht</summary>
    |oak_planks
    |spruce_planks
    |birch_planks
    |jungle_planks
    |acacia_planks
    - minecraft:dark_oak_planks
    - minecraft:mangrove_planks
    - minecraft:cherry_planks
    - minecraft:bamboo_planks
    - minecraft:crimson_planks
    - minecraft:warped_planks
    - minecraft:oak_slab
    - minecraft:petrified_oak_slab
    - minecraft:spruce_slab
    - minecraft:birch_slab
    - minecraft:jungle_slab
    - minecraft:acacia_slab
    - minecraft:dark_oak_slab
    - minecraft:mangrove_slab
    - minecraft:cherry_slab
    - minecraft:bamboo_slab
    - minecraft:bamboo_mosaic_slab
    - minecraft:crimson_slab
    - minecraft:warped_slab
    - minecraft:stone
    - minecraft:cobblestone
    - minecraft:mossy_cobblestone
    - minecraft:smooth_stone
    - minecraft:stone_bricks
    - minecraft:mossy_stone_bricks
    - minecraft:granite
    - minecraft:polished_granite
    - minecraft:diorite
    - minecraft:polished_diorite
    - minecraft:andesite
    - minecraft:polished_andesite
    - minecraft:cobbled_deepslate
    - minecraft:polished_deepslate
    - minecraft:deepslate_bricks
    - minecraft:deepslate_tiles
    - minecraft:bricks
    - minecraft:mud_bricks
    - minecraft:sandstone
    - minecraft:smooth_sandstone
    - minecraft:cut_sandstone
    - minecraft:red_sandstone
    - minecraft:smooth_red_sandstone
    - minecraft:cut_red_sandstone
    - minecraft:prismarine
    - minecraft:prismarine_bricks
    - minecraft:dark_prismarine
    - minecraft:nether_bricks
    - minecraft:red_nether_bricks
    - minecraft:blackstone
    - minecraft:polished_blackstone
    - minecraft:polished_blackstone_bricks
    - minecraft:end_stone_bricks
    - minecraft:purpur_block
    - minecraft:quartz_block
    - minecraft:smooth_quartz_block
    - minecraft:cut_copper
    - minecraft:exposed_cut_copper
    - minecraft:weathered_cut_copper
    - minecraft:oxidised_cut_copper
    - minecraft:waxed_cut_copper
    - minecraft:waxed_exposed_cut_copper
    - minecraft:waxed_weathered_cut_copper
    - minecraft:waxed_oxidised_cut_copper
    - minecraft:stone_slab
    - minecraft:cobblestone_slab
    - minecraft:mossy_cobblestone_slab
    - minecraft:smooth_stone_slab
    - minecraft:stone_brick_slab
    - minecraft:mossy_stone_brick_slab
    - minecraft:granite_slab
    - minecraft:polished_granite_slab
    - minecraft:diorite_slab
    - minecraft:polished_diorite_slab
    - minecraft:andesite_slab
    - minecraft:polished_andesite_slab
    - minecraft:cobbled_deepslate_slab
    - minecraft:polished_deepslate_slab
    - minecraft:deepslate_brick_slab
    - minecraft:deepslate_tile_slab
    - minecraft:brick_slab
    - minecraft:mud_brick_slab
    - minecraft:sandstone_slab
    - minecraft:smooth_sandstone_slab
    - minecraft:cut_sandstone_slab
    - minecraft:red_sandstone_slab
    - minecraft:smooth_red_sandstone_slab
    - minecraft:cut_red_sandstone_slab
    - minecraft:prismarine_slab
    - minecraft:prismarine_brick_slab
    - minecraft:dark_prismarine_slab
    - minecraft:nether_brick_slab
    - minecraft:red_nether_brick_slab
    - minecraft:blackstone_slab
    - minecraft:polished_blackstone_slab
    - minecraft:polished_blackstone_brick_slab
    - minecraft:end_stone_brick_slab
    - minecraft:purpur_slab
    - minecraft:quartz_slab
    - minecraft:smooth_quartz_slab
    - minecraft:cut_copper_slab
    - minecraft:exposed_cut_copper_slab
    - minecraft:weathered_cut_copper_slab
    - minecraft:oxidised_cut_copper_slab
    - minecraft:waxed_cut_copper_slab
    - minecraft:waxed_exposed_cut_copper_slab
    - minecraft:waxed_weathered_cut_copper_slab
    - minecraft:waxed_oxidised_cut_copper_slab
    - minecraft:glass
    - minecraft:tinted_glas
    - minecraft:white_stained_glass
    - minecraft:light_gray_stained_glass
    - minecraft:black_stained_glass
    - minecraft:brown_stained_glass
    - minecraft:red_stained_glass
    - minecraft:orange_stained_glass
    - minecraft:yellow_stained_glass
    - minecraft:lime_stained_glass
    - minecraft:green_stained_glass
    - minecraft:cyan_stained_glass
    - minecraft:light_blue_stained_glass
    - minecraft:blue_stained_glass
    - minecraft:purple_stained_glass
    - minecraft:magenta_stained_glass
    - minecraft:pink_stained_glass
</details>

---

## Wireless-Redstone
Die beiden Schaltungen MC1110 und MC1111 geben dir die Möglichkeit, „Wireless Redstone“ („Kabelloses Redstone“) zu verwenden. Die genaue Verwendung wird gut in der offiziellen Dokumentation von CraftBook beschrieben:
- MC1110 „Transmitter“ („Sender“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1110/)
- MC1111 „Receiver“ („Empfänger“): [CraftBook-Wiki](https://craftbook.enginehub.org/en/latest/mechanics/ics/MC1111/)

Beachte: Vor dem „Transmitter“ muss die Redstone Leitung mindestens zwei Blöcke lang sein, da die Schaltung ansonsten unter Umständen nicht funktioniert. Am Receiver muss ggf. ein “s” ergänzt werden ("[MC1111]s"), um die Funktionalität zu gewährleisten.

---

## Redstone-Jukebox
Jukeboxen können mit Redstone gesteuert werden, um eingelegte Schallplatten zu starten. Das Redstone-Signal startet die Schallplatte auch neu, wenn sie bereits läuft. Das Stoppen ist aufgrund von Limitierungen nicht möglich, dies passiert weiterhin nur dann, wenn die Schallplatte beendet ist oder ausgeworfen wird.
