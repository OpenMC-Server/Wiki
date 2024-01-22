---
label: PlayerWarps
layout: default
order: 697
icon: star
---

# PlayerWarps

PlayerWarps sind Warps, die von Spielern gesetzt werden können. Mit diesen kann beispielsweise ein Shop beworben oder ein Bauwerk für die Öffentlichkeit zugänglich gemacht werden. Über das [!badge variant="light" text="/pwarp"] Menü kannst du dich zu einem beliebigen PlayerWarp teleportieren.

## PlayerWarp erstellen
Mit [!badge variant="light" text="/pwarp set <warpname>"] wird ein PlayerWarp an der Stelle, wo du den Befehl eingibst, erstellt. Dies kostet je PlayerWarp 5000$. Wie viele PlayerWarps du erstellen kannst, kannst du der folgenden Tabelle entnehmen:

{.compact}
Feature                     | Spieler | Siedler | VIP   | VIS   | + Upgrade | Champion
:---:                       | :---:   | :---:   | :---: | :---: | :---:     | :---:
PlayerWarps¹                | 1       | 2       | 1     | 2     | 5         | 5

¹ Auch beim Wechsel auf einen niedrigeren Rang bleiben bereits gesetzte PlayerWarps erhalten.

Um deinen erstellten Warp anschließend einer Kategorie zuzuweisen, nutze den Befehl [!badge variant="light" text="/pwarp category set <warpname> <bauwerke/farmen/shop/sonstiges>"]. So können ihn andere Spieler leichter finden.

## Befehle
Mögliche Aliase: [!badge variant="light" text="/pwarp"] [!badge variant="light" text="/pw"] [!badge variant="light" text="/playerwarp"]

[!badge variant="light" text="/pwarp"]\
Öffnet das PlayerWarp-Menü, mit welchem du dich zu den PlayerWarps teleportieren kannst.

[!badge variant="light" text="/pwarp help"]\
Zeigt alle PlayerWarp Befehle an.

[!badge variant="light" text="/pwarp <warpname>"]\
Teleportiert dich zu dem angegebenen PlayerWarp.

[!badge variant="light" text="/pwarp set <warpname>"]\
Erstellt einen PlayerWarp mit dem angegebenen Namen an der Stelle, wo du den Befehl eingibst.\
Hinweis: Das Erstellen eines PlayerWarps kostet 5000$.

[!badge variant="light" text="/pwarp remove <warpname>"]\
Entfernt den angegebenen PlayerWarp.

[!badge variant="light" text="/pwarp amount"]\
Zeigt die Anzahl an PlayerWarps an, die du noch erstellen kannst.

[!badge variant="light" text="/pwarp reset <warpname>"]\
Setzt den PlayerWarp an die Stelle um, an der du stehst.

[!badge variant="light" text="/pwarp desc set <warpname> <beschreibung>"]\
Mit diesem Befehl kannst du eine Beschreibung zu deinem PlayerWarp eingeben, welche im Menü angezeigt wird.

[!badge variant="light" text="/pwarp category set <warpname> <bauwerke/farmen/shop/sonstiges>"]\
Sortiert den PlayerWarp in eine der vier Kategorien ein.

[!badge variant="light" text="/pw-visits"]\
Schaltet Besucher-Benachrichtigungen, wenn sich jemand zu deinem Playerwarp teleportiert, an oder aus.