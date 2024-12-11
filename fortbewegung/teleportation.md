---
label: Teleportation
layout: default
order: 698
icon: paper-airplane
---

# Teleportation

Damit du schneller an dein Ziel kommst, kannst du dich auf verschiedene Arten teleportieren.

---

## Welten
Auf OpenMC gibt es mehrere Welten, welche jeweils für unterschiedliche Aktivitäten genutzt werden können.

### Bauwelt
`/bauwelt`\
Teleportiert dich in die Bauwelt. Hier kannst du deine Bauwerke errichten, jedoch keine Ressourcen farmen oder Farmen betreiben.

`/bauwelt-nether`\
Teleportiert dich in den Nether der Bauwelt.

### Farmwelt
`/farmwelt`\
Teleportiert dich in die Farmwelt. Hier kannst du ohne Bedenken Ressourcen farmen, da die Welt regelmäßig zurückgesetzt wird.

`/farmwelt-nether`\
Teleportiert dich in den Nether der Farmwelt.

`/farmwelt-end`\
Teleportiert dich in das End der Farmwelt.

### Industriewelt
`/industriewelt`\
Teleportiert dich in die Industriewelt. Hier kannst du große Farmanlagen errichten, ohne die Spieler in den anderen Welten zu beeinträchtigen.

`/industriewelt-nether`\
Teleportiert dich in den Nether der Industriewelt.

### Eventwelt
`/events`\
Teleportiert dich in die Eventwelt.

### Serverwechsel-Befehl
`/serverwechsel [server]`
Teleportiere dich auf einen ausgewählten Server, um an die gleiche Stelle zu kommen wo du vorher gewesen bist. Stehst du also in der Bauwelt an deinem Haus und in der Farmwelt in deiner Höhle, kannst du mit `/serverwechsel Farmwelt` zu deiner Höhle und anderums genau so nach Hause. Während der Nutzung des Befehls wird kein `/back` registriert: Verwendest du `/serverwechsel` ohne einem bestimmten Server, wird dir eine Liste der für dich vorhandenen Server angezeigt.
---

## Homes
Mit Homes kannst du Positionen speichern, um dich anschließend zu diesen zu teleportieren.

### Befehle
`/sethome <homename>`\
Setzt ein Home. Dabei wird dein aktueller Ort und die Blickrichtung gespeichert.\
Wie viele Homes du setzen kannst, kannst du der folgenden Tabelle entnehmen:

{.compact}
Feature                     | Spieler | Siedler | VIP   | VIS   | + Upgrade | Champion
:---:                       | :---:   | :---:   | :---: | :---: | :---:     | :---:
Homes¹                      | 10      | 30      | 50    | 50    |           | 50

¹ Auch beim Wechsel auf einen niedrigeren Rang bleiben bereits gesetzte Homes erhalten.

`/home <homename>`\
Teleportiert dich zum angegebenen Home.

`/delhome <homename>`\
Löscht das angegebene Home.

`/homes`\
Zeigt alle deine Homes an.

---

## Warps
Warps sind Teleportpunkte, die vom Server gesetzt werden und für alle verfügbar sind.

### Befehle
`/warps`\
Zeigt alle verfügbaren Warps an.

`/warp <warpname>`\
Teleportiert dich zum angegebenen Warp.

---

## Spielerteleportation
Über die Spielerteleportation kannst du dich zu einem anderen Spieler teleportieren oder diesen anfragen, sich zu dir zu teleportieren.

### Befehle
`/tpa <spieler>`\
Sendet eine Teleportationsanfrage an den angegebenen Spieler.

`/tpahere <spieler>`\
Sendet eine Anfrage an den angegebenen Spieler, sich zu dir zu teleportieren.

`/tpaccept`\
Mit diesem Befehl kannst du eine an dich gesendete Teleportationsanfrage akzeptieren.

`/tpdeny`\
Mit diesem Befehl kannst du eine an dich gesendete Teleportationsanfrage ablehnen.

`/tpalock deny`\
Blockiert alle eingehenden TPA-Anfragen.

`/tpalock off`\
Aktiviert alle eingehenden TPA-Anfragen.