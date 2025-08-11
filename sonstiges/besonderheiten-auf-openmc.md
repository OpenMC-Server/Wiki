---
label: Besonderheiten auf OpenMC
layout: default
order: 295
icon: flame
---

# Besonderheiten auf OpenMC
Hier findest du serverspezifische Besonderheiten, welche sich vom Vanilla-Gameplay unterscheiden.

---

## Betten / TnT-Explosionen / TnT-Duping
Die Explosion von Betten und TnT in der Farmwelt sind deaktiviert, um das Farmen von Netherite anspruchsvoller zu gestalten.\
TnT-Duping ist nicht möglich und in allen Welten untersagt.

Die Explosionen in anderen Welten können auf dem eigenen Claim mit `/claimexplosions` aktiviert werden.

---

## Mobs
Um ein angenehmes Spielerlebnis für alle zu ermöglichen, unterscheidet sich die Konfiguration des Mob-Verhaltens von der Vanilla-Version. Insbesondere beim Bau von Farmen ist dies zu berücksichtigen, da Funktionalität und Ertrag deutlich abweichen können.

### Mobspawning
In allen Welten spawnen weniger Mobs als in der Vanilla-Version von Minecraft üblich. Ebenfalls despawnen Mobs schneller als normal, damit die Hardware nicht länger als notwendig belastet wird.

Das Mobspawning in der Bauwelt ist am stätksten beschränkt, da sich dort die meisten Spieler aufhalten und der Fokus weniger auf der Interaktion mit Mobs liegt.\
In der Farm- und Industriewelt wurden die Spawnraten ebenfalls verringert, jedoch nicht so stark wie in der Bauwelt.

### Moblimits
Im Gegensatz zum Mobspawning bezieht sich das Moblimit auf bereits bestehende Mobs im Bereich des Spielers.\
Mobs, welche das Limit überschreiten, werden entfernt, es sei denn, sie sind gezähmt oder mit einem Nametag benannt.

Limits in den Welten:
- Bauwelt: 100 Mobs im Bereich des Spielers (3x3 Chunks)
- Industriewelt: 400 Mobs im Bereich des Spielers (3x3 Chunks)

Überprüfbar ist das ganze zusätzlich mit dem Befehl `/chunkinfo`.

---

## View- & Simulation-Distance

{.compact}
Welt            | View-Distance | Simulation-Distance
:---:           | :---:         | :---:
Bauwelt         | 6             | 4
Industriewelt   | 8             | 8
Farmwelt        | 10            | 10

---

## Item-Despawn Verhalten
Die Despawnzeit beträgt standardmäßig für alle Items 5 Minuten.

Ausgenommen sind:
- Bruchstein (15 Sekunden)
- Netherrack (15 Sekunden)

---

## Phantome
Phantome sind in der gesamten Bauwelt deaktiviert. In der Industrie- und Farmwelt lässt sich das Spawning mit `/phantomspawn` steuern.

---

## Schmiedevorlagen Rezept
Die Rezepte der Schmiedevorlagen wurden verteuert, um das Spielgeschehen anspruchsvoller zu gestalten.\
Das angepasste Rezept findest du unter [CustomCrafting](/besondere-funktionen/customcrafting.md).

Schmiedevorlagen für die Netherite-Aufwertung sind nicht vom neuen Rezept betroffen.

---

## Schwerkraft von Rüstungsständern
Armorstands unterliegen nicht den normalen Minecraft Gravitationsregeln und haben somit keine Schwerkraft.

---

## Netherportale in der Industriewelt
Die Blockreichweite zwischen der Oberfläche und dem Nether beträgt in Minecraft bekanntlich eine Aufteilung von 1:8. Das heißt, dass 8 Blöcke an der Oberfläche etwa 1 Block im Nether entsprechen.

In der Industriewelt besteht die Besonderheit, dass vom Spawn aus 1000 Blöcke nicht geclaimt werden kann. Darüber hinaus ist die Industriewelt mit einer Border von zurzeit 35k limitiert. Das bedeutet auf das Verhältnis hinaus:
- dass im Nether zu den Koordinaten < 8000 Blöcke die Chance bestehen könnte, dass ein Portal nicht funktioniert (`8000 / 8` entspricht den 1000 Blöcken vom Spawn, in denen man nicht bauen kann).
- dass ein Portal im Nether, was zu weit hinter der Border an der Oberfläche nach dem Verhältnis ist, womöglich ebenfalls nicht funktionieren wird (Die Koordinate `7000 * 8` entspricht 56.000 Blöcken, was an der Oberfläche bereits hinter der Border ist.).