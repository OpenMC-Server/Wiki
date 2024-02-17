---
label: Transaktionshistorie
layout: default
order: 596
icon: project-roadmap
---

# Transaktionshistorie

!!!primary Im Aufbau
Hier findest du in Kürze Informationen zur Transaktionshistorie.
!!!

Anhand der Transaktionshistorie kannst du deine Ein- & Ausgaben auf dem Server im Auge behalten und teils sogar filtern. Hierbei gilt meistens die Sicht, dass das Geld aus /balance in eine andere Quelle hinein oder aus einer Quelle heraus gebracht wird. Meistens deshalb, weil auch Ausnahmen manchmal vorkommen können, welche du im Verlauf des Artikels kennenlernen wirst.

## Transaktionshistorie aufrufen
Öffne mit `/transactions all` alle deine Transaktionseinträge. Hier findest du bis zu 6 unterschiedliche Kategorien, durch welche du mit deinem Geld handel betreiben kannst. Wenn du gezielt filtern möchtest, kannst du ebenfalls `/transactions <category>` oder überall sonst auch kurz `/th <category>` verwenden. Sofern spezielle Angaben zu einem Eintrag existieren, kannst du diese durch das Hovern (Mauszeiger über die Nachricht) einsehen.

![](/images/transaktionshistorie.png)

---

### Transaktionsarten
Transaktion         | Nutzen                                                                            |
---                 | ---                                                                               |
all                 | Alle deine Transaktionen                                                          |
admin_shop	        | Transaktionen mit dem [Adminshop](https://wiki.openmc.net/geld-level/adminshop/)  |
chest_shop	        | Transaktionen mit [ChestShops](https://wiki.openmc.net/geld-level/chestshop)      |
bank	            | Transaktionen mit deinem Tresor                                                   |
jobs	            | Transaktionen mit deinen [Jobs](https://wiki.openmc.net/geld-level/jobs)          |
console_pay	        | Transaktionen, die der Server bei dir auf `/balance` vornimmt                     |
player_pay	        | Transaktionen, die du mit Spielern über `/pay` vornimmst                          |
tresor              | Transaktionen von dir auf die Bank, oder vom Server auf deine Bank (`/tresor`)    |
unread	            | Transaktionen, die von dir noch nicht gelesen wurden                              |
current             | Öffnet deine zuletzt genutzte Historie, sofern sie noch vorhanden ist             |

---

### Ausnahmen in Transaktionen
#### ChestShops
ChestShop-Transaktionen können sowohl von dir (An- & Verkauf), als auch von anderen Spielern bei dir vorgenommen werden. Das macht insgesamt 4 unterschiedliche Ergebnisse in der Transaktionshistorie, wodurch du mehr oder weniger gezwungen sein würdest, über die Nachricht zu hovern um zu Erfahren, ob du oder dein Mitspieler die Transaktion vollzogen hat. Aus diesem Anlass werden deine eigenen Transaktionen wie oben ersichtlich mit einem Stern markiert.

#### Tresor/Bank
Bank ist hier das Pseudonym zur `/tresor`-Funktion und stellt Einträge von dir da, wenn du Geld in deinen Tresor ein- oder auslagerst. Aus Sicht des `/balance` Betrags werden Transaktionen von dir wie folgt dargestellt:
- Du => Tresor als **negative Beträge** (Betrag schwindet aus `/balance`)
- Tresor => Dir als **positive Beträge** (Betrag fließt in `/balance` ein)

Die Ausnahme gilt dann, wenn der Server jedoch Geld in deinem Tresor verwaltet. In dem Fall gilt das ganze anders herum:
- Server => Tresor = Positiv
- Tresor => Server = Negativ

Was von beidem tatsächlich der Fall ist, kannst du Stand jetzt aus der Hover-Nachricht entnehmen.
