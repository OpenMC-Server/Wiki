---
label: ClaimFlags
layout: default
order: 798
icon: tag
---

# ClaimFlags

Mit Claimflags können zusätzliche Funktionen auf Claims aktiviert werden.

Um diese aktivieren oder deaktivieren zu können, müssen die gewünschten Flags vorher im `/claimflags` Menü freigeschaltet werden.\
Auf einem Claim kann eine Flag anschließend mit `/setclaimflag <flagname> [optionen]` aktiviert werden.

Ein Kauf erfolgt dauerhaft und berechtigt zur Aktivierung auf allen eigenen Claims.

---

## Befehle
`/claimflags`\
Öffnet das Menü zum freischalten der Flags.

`/setclaimflag <flagname> [optionen]`\
Setzt eine Flag auf einem Claim.

`/unsetclaimflag <flagname>`\
Entfernt eine Flag von einem Claim.

`/listclaimflags`\
Zeigt alle aktiven Flags.

---

## Liste der Flags

Flag                    | Erklärung | Preis
---                     | ---       | ---
AllowBlockExplosions    | Blockeplosionen dauerhaft aktivieren. | 50k $
BuyAccessTrust          | Spieler können mit `/buyaccesstrust` für einen einstellbaren Betrag AccessTrust auf dem Claim kaufen. | 65k $
BuyBuildTrust           | Spieler können mit `/buybuildtrust` für einen einstellbaren Betrag BuildTrust auf dem Claim kaufen. | 65k $
BuyContainerTrust       | Spieler können mit `/buycontainertrust` für einen einstellbaren Betrag ContainerTrust auf dem Claim kaufen. | 65k $
BuySubclaim             | Spieler können mit `/buysubclaim` für einen einstellbaren Betrag den Subclaim kaufen, in welchem die Flag aktiviert wurde. Der Käufer erhält vollständigen Trust im Subclaim. Nach dem Kauf wird die Flag automatisch entfernt, damit der Subclaim nicht erneut erworben werden kann. | 65k $
EnterMessage            | Nachricht beim Betreten des Claims anzeigen. | 30k $
ExitMessage             | Nachricht beim Verlassen des Claims anzeigen. | 30k $
NoBlockForm             | Das Formen von Schnee, Eis, Obsidian/Cobblestone (Wasser/Lava), Betonpulver/Wasser deaktivieren. | 60k $
NoBlockSpread           | Die Ausbreitung von Blöcken deaktivieren. | 60k $
NoChorusFruit           | Die Verwendung von Chorusfrüchten deaktivieren. | 25k $
NoCoralDeath            | Den Verfall von Korallen deaktivieren. | 75k $
NoDripstoneSpread       | Die Ausbreitung von Dripstones deaktivieren. | 50k $
NoEnderPearl            | Die Verwendung von Enderperlen deaktivieren. | 25k $
NoFallDamage            | Fallschaden deaktivieren. | 15k $
NoGrowth                | Das Wachstum von Erntepflanzen (Crops) deaktivieren. | 60k $
NoHunger                | Hunger deaktivieren. | 60k $
NoIceForm               | Bildung von Eis deaktivieren. | 50k $
NoLeafDecay             | Das Verschwinden von Blättern deaktivieren. | 40k $
NoMcMMOSkills           | Aktive Skill-Aktivierung (z.B. Faustkampf) deaktivieren. | 100k $
NoMobSpawns             | Das Spawning von allen Mobs deaktivieren. Bestehende Mobs bleiben erhalten. | 150k $
NoMonsters              | Monster deaktivieren. Alle bestehenden Monster despawnen. | 150k $
NoMonsterSpawns         | Das Spawning von Monstern deaktivieren. Bestehende Monster bleiben erhalten. | 150k $
NoPotionEffects         | Trankeffekte deaktivieren. | 100k $
NoSnowForm              | Bildung von Schnee deaktivieren. | 50k $
NoStructureGrowth       | Das Wachstum von Setzlingen, Pilzen und Chorusfrüchten deaktivieren. | 50k $
NoVineGrowth            | Das Wachstum von Ranken und Leuchtbeeren deaktivieren. | 50k $
ProtectNamedMobs        | Benannte Mobs dürfen nur mit ContainerTrust geschlagen werden. Gilt auch für Owner. | 30k $
RaidMemberOnly          | Fremde Spieler können keine Raids auf dem Claim starten. | 25k $
ReadLecterns            | Das Lesen signierter Bücher in Lesepulten erlauben. | 20k $
NoEnter [Industriewelt] | Das Betreten des Claims durch fremde Spieler deaktivieren. | 0 $
NoMapMaking             | Das Erstellen von Maps durch fremde Spieler deaktivieren. | 0 $
CommandBlacklist        | Die Verwendung bestimmter Befehle deaktivieren. | Beim Team beantragbar
ViewContainer           | Kisten können geöffnet werden, aber es ist nicht möglich Items zu entnehmen. | Beim Team beantragbar
KeepInventory           | Items werden nach dem Tod im Inventar beibehalten | Beim Team beantragbar für **Arenen**
RespawnLocation         | Setze den Respawn-Punkt nach dem Tod auf dem Grundstück | Beim Team beantragbar für **Arenen**

Sollte eine Flag aus technischen oder konzeptionellen Gründen einmal entfernt werden, kann eine Rückerstattung beantragt werden.