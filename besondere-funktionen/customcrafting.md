---
label: CustomCrafting
layout: default
order: 399
icon: cpu
---

# CustomCrafting [!button target="blank" size="xs" variant="success" icon=":bulb:" text="Feedback geben"](https://tally.so/r/WO8gxJ)

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

## Anwendung des Craftingsystems

### Öffnen des Craftingmenüs

Über die Befehle `/crafting` oder `/craft use crafting` gelangst du in das Craftingmenü. Dort findest du unterschiedliche Kategorien für die Rezepte:

-![](/images/customcrafting_kategorien.png)

Innerhalb einer Kategorie werden die jeweiligen Rezepte angezeigt:  
-![](/images/customcrafting_rezepte.png)

---

#### Rezeptkosten und Voraussetzungen
- **Rezeptkosten** sind die Materialien, das Geld oder die Vanilla-Exp, die für ein Rezept benötigt werden. Diese werden beim Craften **verbraucht**.  
- **Voraussetzungen** sind Bedingungen, die erfüllt sein müssen, um ein Rezept nutzen zu können. Diese bleiben dir auch nach dem Craften **erhalten**.  

Mögliche Voraussetzungen:  
- McMMO-Level  
- Job-Level  
- Professions-Level (siehe [Ausblick](#ausblick))  
- Abenteurer-Level (siehe [Farmwelt-Konzept](https://discord.com/channels/593436350829690899/598209493444198424/1369789201976918127))
- Crafting-Limit (Ein Item darf nur `x` Mal gecraftet werden)  

---

#### Die Rezept-Warteschlange

Jede Kategorie verfügt über **3 Craftingslots**. Dort werden die Rezepte in eine Warteschlange gelegt.  

- Das erste Rezept beginnt automatisch mit der Abarbeitung seines Cooldowns.  
- Klickst du ein Rezept vor Abschluss erneut an, erhältst du die eingesetzten Ressourcen zurück (bei vollem Inventar werden diese gedroppt).  
- Nach Abschluss kannst du das fertige Item durch einen **Linksklick** ins Inventar aufnehmen.  
- Über einen **Rechtsklick** hingegen werden alle Items aufgesammelt, welche schon abgeschlossen sind.

⚙️ **Wichtige Hinweise:**  
- Pro Kategorie kann immer nur **ein Rezept gleichzeitig** bearbeitet werden.  
- Auch wenn die Warteschlange nur 3 sichtbare Slots hat, können insgesamt **bis zu 100 Items** gleichzeitig gecraftet werden.  
- Bei vollem Inventar werden die Resultate auf dem Boden gedropped.
- Die restlichen Slots erreichst du über die Navigation am Rand:  
-![](/images/customcrafting_warteschlange.png)

---

### Shard-System
Shards sind zurzeit ein wichtiger Bestandteil der meisten CustomCrafting-Rezepte. Es gibt drei Stufen an Shards, “Shard I”, “Shard II” und Shard “III”. Diese bauen aufeinander auf – das bedeutet, dass Shards einer niedrigeren Stufe benötigt werden, um Shards einer höheren Stufe zu erhalten.

Die einzige Besonderheit dabei sind Shard III. Er ist als Drop bei [Bosskämpfen](/geld-level/bosskampf.md) erhältlich und ist deshalb für die seltensten und teuersten Rezepte reserviert.
Unter `/craft use crafting:Zutaten` kannst du unter anderem viele Zutaten entdecken, welche Shards als Grundzutat verwenden.

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