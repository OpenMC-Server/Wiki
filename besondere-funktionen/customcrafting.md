---
label: CustomCrafting
layout: default
order: 399
icon: cpu
---

# CustomCrafting

[!badge :white_check_mark: Ingame-Tutorial verfügbar: `/warp tutorial_customcrafting (in Arbeit)`]

Auf dem Server verstehen wir unter **CustomCrafting** die Einführung neuer Items sowie der dazugehörigen Rezepte. Damit bietet OpenMC die Möglichkeit, über eigens entwickelte Items ein individuelles und einzigartiges Spielerlebnis zu schaffen.

---

## Migration von veralteten Items
Um im neuen Craftingsystem weiterhin deine bestehenden Custom-Items verwenden zu können, müssen diese in das neue Plugin umziehen. Besonders wichtig sind alle Items, welche als `Zutat` oder `Ausrüstung` in CustomCrafting erhältlich sind wie zum Beispiel:
- Shard I, II, III
- Shulkerkerne, Schulker Beschwörungsstein
- Phiole
- Stürmischer Dreizack (ehemals `Verbesserter Dreizack`)
- Wirbelsturm Brustplatte
- Verdorrntes Schild (ehemals `Verbessertes Schild`)
- Alle Custom-Items aus den **VoteChests**

Sammelitems wie Bauevent-Belohnungen, Halloween- & Weinachtskram etc. können umgetauscht werden, müssen es aber **nur dann, wenn sie einzigartige Effekte** mit sich bringen (Kürbissoldatrüstung, Gamescom-Item, Elfenschuhe, etc.). Items wie Gebäck aus Weihnachten sind auch Umtauschbar, jedoch mit keinem großen Einfluss verbunden.

*Darüber hinaus sehen wir im Umtauschprozess vor, missentwickelte Gegestände im angepassten Format zurückzugeben. Wenn diese für die zukünftige Konzeption vom System notwendig sind, können diese Items ebenfalls erzwungen umgetauscht werden.*

### Umtauschprozess
Um deine veralteten Items umzutauschen, kannst du uns an einem Ort Kisten aufstellen und die Koordinaten über ein Ticket mitteilen. 

*Die veralteten Items sind bis einschließlich Dezember 2025 noch funktionsfähig. Danach wird das alte Plugin abgeschaltet, sodass nur noch der Umtausch die Itemfunktion wiederherstellen kann.*

### Liste mit notwendigem Umtausch

!!!warning
Die Liste ist fortlaufend und wird mit der Zeit erweitert.
Falls ihr eure Items mit besonderen **Features** (siehe unten) nicht wiederfindet, gebt mir bitte Bescheid, damit die Liste aktualisiert werden kann.

**Wichtig:**
* Diese Items sind notwendig.
* Andere Items können **optional** umgetauscht werden, zum Beispiel wenn sie für Shops oder ähnliche Zwecke einheitlich benötigt werden.
!!!

+++ Event-Items / Sammelitems
- Kürbissoldaten-Rüstung (Helm, Brustplatte, Hose, Schuhe)
  - Geschwindigkeit hängt davon ab
- Gamescom-Item
  - Geschwindigkeit hängt davon ab
- Elfenschuhe
  - Sprungkraft hängt davon ab
- Werwolfsrüstung (Helm, Brustplatte, Hose, Schuhe)
  - Schaden hängt davon ab
- Vampirrüstung (Helm, Brustplatte, Hose, Schuhe)
  - Schaden & Extra-Effekte hängen davon ab
- Weihnachtstools (Spitzhacke, Axt, Schaufel, Angel, Schwert)
  - Geschwindigkeit hängt davon ab
- Weihnachtsrüstung
  - Extra-Herzen hängen davon ab
- Schaufel des Schneemans
  - Schneeball-Schuss hängt davon ab
- Seelensense
  - Funktionalität hängen davon ab
- Tarnmantel
  - Funktionalität hängen davon ab
- Finsterauge
  - Funktionalität hängen davon ab
- Magische Miesmuschel
  - Funktionalität hängen davon ab


+++ Ausrüstung & Verbrauchsgüter
- Mighty X Brustplatte
  - Benötigt für Weiterverarbeitung
- Deepslate-Spitzhacke
  - Geschwindigkeit hängt davon ab
- Verbesserter Dreizack I, II & III
  - Überarbeitung
- Verbessertes Schild I, II & III
  - Überarbeitung
- Wirbelsturm Brustplatte I, II & III
  - Überarbeitung
- Unsichtbare Itemframes
  - Überarbeitung, Sichtbarkeit hängt ab
- MuteTags
  - Muting von Entities hängt davon ab
- Beschwörungsstein: Schulker
  - Shulkerbeschwörung hängt davon ab


+++ Ressourcen & Sonstiges
- Shard I, II & III
- Stramme Seide
- Phiole
- Shardessenz
- Shulker-Kern
- Collector Chest Blumen (Freedom, Hope, Justice, Love, Faith)

-> Benötigt für Weiterverarbeitung

+++

---

## Aufbau des Craftingsystems

Die Rezepte sind in verschiedene Kategorien unterteilt. Zum Start existieren die Kategorien **Zutaten** und **Handwerkskunst**.  

- In der Kategorie **Zutaten** findest du alle Rezepte, die Items für die Weiterverarbeitung liefern.  
- In der Kategorie **Handwerkskunst** werden die finalen Produkte hergestellt.  

Jede Kategorie kann in mehrere Unterkategorien aufgeteilt sein, um die Übersichtlichkeit zu gewährleisten.

### Einordnung

+++ Zutaten
- **Blaupausen** (Vorlagen für Ausrüstung)  
- **Zutaten zur Weiterverarbeitung** (Materialien für Ausrüstung)  
- **Verschiedenes** (z. B. Armor Trims)  

+++ Handwerkskunst
- **Rüstung**  
- **Waffen**  
- **Werkzeuge**  
- **Verbrauchsgüter**  

+++

---

### Anwendung des Craftingsystems

#### Öffnen des Craftingmenüs

Über die Befehle `/craft use zutaten` oder `/craft use handwerkskunst` gelangst du in das Craftingmenü. Dort kannst du zwischen den Kategorien nahtlos wechseln:

+++ Zutaten-GUI
![](/images/customcrafting_zutaten_zu_handwerkskunst.png)

+++ Handwerkskunst-GUI
![](/images/customcrafting_handwerkskunst_zu_zutaten.png)

+++

Innerhalb einer Unterkategorie werden die jeweiligen Rezepte angezeigt:  
![](/images/customcrafting_rezept_beispiel.png)

---

#### Rezeptkosten und Voraussetzungen
- **Rezeptkosten** sind die Materialien, das Geld oder die Vanilla-Exp, die für ein Rezept benötigt werden. Diese werden beim Craften **verbraucht**.  
- **Voraussetzungen** sind Bedingungen, die erfüllt sein müssen, um ein Rezept nutzen zu können. Diese bleiben dir auch nach dem Craften **erhalten**.  

Mögliche Voraussetzungen:  
- McMMO-Level  
- Job-Level  
- Professions-Level (`zutaten`, `handwerkskunst`, siehe [Ausblick](#ausblick))  
- Abenteurer-Level (siehe [Farmwelt-Konzept](https://discord.com/channels/593436350829690899/598209493444198424/1369789201976918127))
- Crafting-Limit (Ein Item darf nur `x` Mal gecraftet werden)  

---

#### Die Rezept-Warteschlange

Jede Unterkategorie verfügt über **3 Craftingslots**. Dort werden die Rezepte in eine Warteschlange gelegt.  

- Das erste Rezept beginnt automatisch mit der Abarbeitung seines Cooldowns.  
- Klickst du ein Rezept vor Abschluss erneut an, erhältst du die eingesetzten Ressourcen zurück (bei vollem Inventar werden diese gedroppt).  
- Nach Abschluss kannst du das fertige Item durch einen **Linksklick** ins Inventar aufnehmen.  
- Über einen **Rechtsklick** hingegen werden alle Items aufgesammelt, welche schon abgeschlossen sind.

⚙️ **Wichtige Hinweise:**  
- Pro Unterkategorie kann immer nur **ein Rezept gleichzeitig** bearbeitet werden.  
- Auch wenn die Warteschlange nur 3 sichtbare Slots hat, können insgesamt **bis zu 100 Items** gleichzeitig gecraftet werden.  
- Bei vollem Inventar werden die Resultate auf dem Boden gedropped.
- Die restlichen Slots erreichst du über die Navigation am Rand:  
![](/images/customcrafting_warteschlange.png)

---

### Shard-System
Shards sind zurzeit ein wichtiger Bestandteil der meisten CustomCrafting-Rezepte. Es gibt drei Stufen an Shards, “Shard I”, “Shard II” und Shard “III”. Diese bauen aufeinander auf – das bedeutet, dass Shards einer niedrigeren Stufe benötigt werden, um Shards einer höheren Stufe zu erhalten.

Die einzige Besonderheit dabei sind Shard III. Er ist als Drop bei [Bosskämpfen](/geld-level/bosskampf.md) erhältlich und ist deshalb für die seltensten und teuersten Rezepte reserviert.
Unter `/craft use zutaten:weiterverarbeitung` kannst du unter anderem viele Zutaten entdecken, welche Shards als Grundzutat verwenden.

---

### Befehle

- `/craft use <profession>`  
  Öffnet das Craftingmenü eines bestimmten Rezeptpfades.  

- `/craft use <profession>:<category>`  
  Öffnet das Craftingmenü einer spezifischen Kategorie eines Rezeptpfads.  

- `/craft show`  
  Das Item, welches du in der Hand hältst wird nach allen möglichen Custom-Rezepten überprüft. Danach kannst du über einen Linksklick auf den jeweiligen Rezeptpfad gelangen.
  
- `/craft stats`  
  Zeigt das Level deines aktiven Rezeptpfads an.  

!!!warning
Aktuell können Rezeptpfade noch nicht gelevelt werden. Diese Funktion wird im Zuge des neuen [Farmwelt-Konzepts](https://discord.com/channels/593436350829690899/598209493444198424/1369789201976918127) eingeführt.
!!!

---

### Ausblick

Die Umstellung auf das neue Craftingsystem bringt zunächst nur die bestehenden Custom-Rezepte in das neue Plugin. Abgesehen von leichten Änderungen bei den Zutaten bleibt alles weitgehend unverändert.  

Mit der Einführung des Farmwelt-Konzepts (Dungeons, Skills, Quests, etc.) werden jedoch viele neue Zutaten und Rezepte hinzukommen. Auch neue Kategorien sind möglich.  

Langfristig werden die Kategorien – dann **Professionen** genannt – **levelbar** sein. Bestimmte Rezepte werden erst ab einem bestimmten Level freigeschaltet.  

<!--
## Rezepte
Im Folgenden findest du eine Auflistung aller CustomCrafting Rezepte.

Du kannst außerdem `/reciepes` nutzen, um dir die Rezepte ingame anzusehen. Zusätzlich sind alle Rezepte in das Minecraft-Rezeptbuch in den Werkbänken integriert. Alternativ kannst du das Rezeptbuch auch craften:
==- Rezeptbuch
![](/images/rezeptbuch.png)-
- 1 Leuchtsteinstaub
- 1 Buch
==-

### Rezept-Zutaten
Allgemeine Rezepte, die für das weitere Crafting verwendet werden.

==- Pfeilvorlage
![](/images/pfeilvorlage.png)-
Material zur Erstellung von neuen Pfeilen.
- 4 Shard I
- 32 Drachenatem
- 64 Pfeil

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Dreizack Blaupause
![](/images/dreizack_blaupause.png)-
Vorlage für neue Waffen.
- 4 Shard II
- 1 Verzaubertes Buch (Reparatur)
- 1 Verzaubertes Buch (Harpune V)
- 1 Verzaubertes Buch (Haltbarkeit III)
- 1 Verzaubertes Buch (Treue III)
- 1 Dreizack

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Elytra Blaupause
![](/images/elytra_blaupause.png)-
Vorlage für neue Elytren.
- 2 Shard I
- 2 Shard II
- 1 Elytren

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Phiole
![](/images/phiole.png)-
Glasbehälter zum Verstauen von Substanzen.
- 1 Stramme Seide
- 3 Glas
- 1 Shard I

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Shard II
![](/images/shard_2.png)-
- 4 Shard I
- 3 Shard-Essenz
- 64 Goldblock
- 16 Phantomhaut

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Shard-Essenz
![](/images/shard_essenz.png)-
Die Essenz eines mittelwertigen Shard.
- 4 Wither-Skelettschädel
- 3 Shard I
- 1 Netheritplatten
- 5 Witherrose

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Shulker-Kern
![](/images/shulker_kern.png)-
Die Lebensessenz einer Shulker.
- 64 Amethystscherbe
- 8 Shard I
- 2 Shard II
- 1 Aquisator

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Stramme Seide
![](/images/stramme_seide.png)-
Material zur Verarbeitung.
- 4 Faden
- 1 Shard I

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Wasser Essenz
![](/images/wasser_essenz.png)-
Material für Items mit Wassereigenschaften.
- 2 Shard II
- 1 Netherstern
- 2 Seltsamer Verweiltrank
- 1 Phiole

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Wind Essenz
![](/images/wind_essenz.png)-
Material für Items mit Windeigenschaften.
- 2 Shard II
- 1 Netherstern
- 2 Verweiltrank des sanften Falls (1:00)
- 1 Phiole

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*
==-

### Ausrüstung
Crafte serverspezifische Waffen, Rüstung und Werkzeuge.

==- Deepslate Spitzhacke
![](/images/deepslate_spitzhacke.png)-
[Effizienz V, Reparatur, Haltbarkeit III]
- 256 Rissige Tiefenschieferfliesen
- 128 Bruchtiefenschiefer
- 2 Shard II
- 1 Netheritspitzhacke

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Wirbelsturm Brustplatte I
![](/images/wirbelsturm_brustplatte_1.png)-
Eine Brustplatte mit Flugeigenschaften.
- 2 Netherstern
- 1 Shard III
- 2 Wind Essenz
- 1 Netheritharnisch
- 1 Elytra Blaupause

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Wirbelsturm Brustplatte I (mit Reparatur)
![](/images/wirbelsturm_brustplatte_1_reparatur.png)-
Eine Brustplatte mit Flugeigenschaften.\
[Reparatur]
- 2 Shard II
- 1 Verzaubertes Buch (Reparatur)
- 1 Enderkristall
- 1 Wirbelsturm Brustplatte I

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Wirbelsturm Brustplatte II
![](/images/wirbelsturm_brustplatte_2.png)-
Eine Brustplatte mit Flugeigenschaften.\
[Reparatur, Haltbarkeit III, Schutz V]
- 2 Wind Essenz
- 1 Verzaubertes Buch (Haltbarkeit III)
- 1 Verzaubertes Buch (Schutz IV)
- 2 Shard II
- 1 Wirbelsturm Brustplatte I (mit Reparatur)

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Wirbelsturm Brustplatte III
![](/images/wirbelsturm_brustplatte_3.png)-
Eine Brustplatte mit Flugeigenschaften.\
[Reparatur, Haltbarkeit V, Schutz X]
- 2 Shard II
- 1 Shard III
- 4 Netherstern
- 2 Wind Essenz
- 1 Mighty X Brustplatte
- 1 Wirbelsturm Brustplatte II

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbesserter Dreizack I
![](/images/verbesserter_dreizack_1.png)-
Geschärfter Kampfdreizack.\
[Reparatur, Schärfe I, Schwungkraft I, Haltbarkeit III, Treue III, Harpune V]
- 1 Wasser Essenz
- 1 Verzaubertes Buch (Schärfe I)
- 1 Verzaubertes Buch (Schwungkraft I)
- 2 Shard I
- 1 Shard III
- 1 Dreizack Blaupause

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbesserter Dreizack II
![](/images/verbesserter_dreizack_2.png)-
Geschärfter Kampfdreizack.\
[Reparatur, Schärfe III, Schwungkraft II, Haltbarkeit III, Treue III, Harpune V]
- 2 Wasser Essenz
- 1 Verzaubertes Buch (Schärfe III)
- 1 Verzaubertes Buch (Schwungkraft II)
- 2 Shard II
- 1 Verbesserter Dreizack I

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbesserter Dreizack III
![](/images/verbesserter_dreizack_3.png)-
Geschärfter Kampfdreizack.\
[Reparatur, Schärfe V, Schwungkraft III, Haltbarkeit III, Treue III, Harpune V]
- 3 Wasser Essenz
- 1 Verzaubertes Buch (Schärfe V)
- 1 Verzaubertes Buch (Schwungkraft III)
- 4 Netherstern
- 1 Shard III
- 1 Verbesserter Dreizack II

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbessertes Schild I
![](/images/verbessertes_schild_1.png)-
Reduziert den erhaltenen Rückstoß.\
[Reparatur, Haltbarkeit III]
- 2 Shard I
- 1 Shard II
- 1 Schild
- 1 Verzaubertes Buch (Haltbarkeit III)
- 1 Verzaubertes Buch (Reparatur)

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbessertes Schild II
![](/images/verbessertes_schild_2.png)-
Reduziert den erhaltenen Rückstoß.\
[Reparatur, Rückstoß I, Haltbarkeit III]
- 2 Shard I
- 1 Shard II
- 1 Verzaubertes Buch (Rückstoß I)
- 1 Verbessertes Schild I

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Verbessertes Schild III
![](/images/verbessertes_schild_3.png)-
Reduziert den erhaltenen Rückstoß.\
[Reparatur, Rückstoß II, Haltbarkeit III]
- 4 Netheritplatten
- 1 Verzaubertes Buch (Rückstoß II)
- 2 Shard II
- 1 Netherstern
- 1 Verbessertes Schild II

**Hinweise:**
- Manuelle Eingriffe zerstören die Itemfunktion.

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==-

### Verbrauchsgüter
Items, die nach bestimmter Nutzungsdauer verbraucht werden.

==- Pfeil der Heilung IV
![](/images/pfeil_der_heilung_4.png)-
Verleiht dem Ziel Heilung IV.
- 4 Verweiltrank der Heilung (Direktheilung II)
- 2 Shard I
- 16 Goldener Apfel
- 1 Pfeilvorlage

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Pfeil der Sprungkraft III
![](/images/pfeil_der_sprungkraft_3.png)-
Verleiht dem Ziel Sprungkraft III.
- 4 Wurftrank der Sprungkraft (Sprungkraft II)
- 2 Verweiltrank der Sprungkraft (Sprungkraft II)
- 2 Shard I
- 1 Pfeilvorlage

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Pfeil des Aufschwungs
![](/images/pfeil_des_aufschwungs.png)-
Befördert das Ziel kurzzeitig in die Luft.
- 4 Verweiltrank der Sprungkraft (Sprungkraft II)
- 2 Verweiltrank des sanften Falls
- 2 Shard I
- 1 Pfeilvorlage

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Stumm-Tag
![](/images/stumm.png)-
Lässt Entitäten verstummen.
- 1 Shard I
- 4 Namensschild
- 2 Phantomhaut

**Hinweise:**
- Das Verwenden aktualisiert die gesamte Umgebung
- Zum Entstummen, Entität mit einem Nametag umbenennen und mit einem Mutetag aktualisieren.

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Shulker Beschwörungsstein
![](/images/shulker_beschwörungsstein.png)-
- 16 Shulker-Schale
- 1 Shulker-Kern

**Hinweise:**
- Muss auf einem Netheriteblock mit einem Rechtsklick verwendet werden
- Im Anschluss verschwinden sowohl der Block als auch das Item und am hinterlassenen Block spawnt der Schulker.

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Hydraulikschalter
![](/images/hydraulikschalter.png)-
Schalte Eisenfalltüren ohne Redstone um.\
64 Nutzungen.
- 16 Kupferbarren
- 16 Redstone-Staub
- 16 Eisenbarren

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- Wiederbelebungstotem-Set
![](/images/wiederbelebungstotem_set.png)-
Ein 3-teiliges Totem-Set zum Wiederbeleben.
- 2 Stock
- 2 Stramme Seide
- 1 Shard II
- 3 Wiederbelebungstotem (durch Mobevent)

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==-

### Vanilla Erweiterungen
Rezepte, die sonst nicht herstellbare Vanilla-Items erzeugen.

==- Kettenstiefel
![](/images/kettenstiefel.png)-
- 4 Kette

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Kettenhemd
![](/images/kettenhemd.png)-
- 8 Kette

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Kettenhaube
![](/images/kettenhaube.png)-
- 5 Kette

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Kettenhose
![](/images/kettenhose.png)-
- 7 Kette

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Versteinerte Eichenholzstufe
![](/images/versteinerte_eichenholzstufe.png)-
- 6 Eichenholzstufe
- 2 Stein
- 1 Eichenholzbretter

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- Shulker-Kiste (farbig)
![](/images/shulker_kiste.png)-
- 2 Shulker-Schale
- 1 Truhe
- 1 Farbstoff

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==- 2x Schmiedevorlage
![](/images/schmiedevorlage.png)-
- 12 Diamantblock
- 2 Witherskelettschädel
- 3 Shard I
- 1 Schmiedevorlage
- 64 Schmiedevorlagen-Material [siehe Minecraft-Wiki](https://de.minecraft.wiki/w/Schmiedevorlage)

*Geformtes Rezept. Die Zutaten müssen in einer exakten Form angeordnet werden.*

==- 2x Shulker-Schale
![](/images/shulker_schale.png)-
- 1 Shulker-Kiste

*Formloses Rezept. Die Zutaten dürfen in einer beliebigen Form angeordnet werden.*

==-

---
-->
