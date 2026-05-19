---
label: MapArts
layout: default
order: 394
icon: image

---

# MapArts

Mit MapArts kannst du die gestalterischen Möglichkeiten in Minecraft erweitern und deiner Kreativität freien Lauf lassen.

!!!base Zukünftiges Feature
Seite in Arbeit.\
Die hier beschriebenden Informationen beziehen sich auf Funktionen, die in den kommenden Tagen veröffentlicht werden.
!!!

## Erbauen von MapArts
Auf OpenMC können MapArts in einer separaten Flachwelt erbaut werden. Diese Welt besitzt der Mapgröße entsprechende Grundstücke ("Plots").

[!badge size="xl" text=":cyclone: Zur Welt: **/warp Bauwelt-Maparts**"]

Jeder Plot ist 132x132 Blöcke groß: 128x128 Blöcke für das MapArt sowie zwei Blöcke als Puffer für die nördliche Reihe sowie die optionale Abschirmung.

TODO: Regeln Mapart-Welt

### Plot beanspruchen
Um einen Plot zu beanspruchen und darauf zu bauen, gibt es zwei Möglichkeiten:

||| :one: Automatische Beanspruchung
Gebe `/plot auto` ein, um einen freien Plot zu beanspruchen.\
Es werden 500 ✪ abgezogen.

**Achtung:** Wenn du ein größeres MapArt erstellen möchtest, nutze stattdessen die manuelle Beanspruchung.
||| :two: Manuelle Beanspruchung
Fliege zu einem freien Plot und gebe `/plot claim` ein.\
Es werden 500 ✪ abgezogen.

**Tipp:** Du kannst die [Basis-Livemap](https://basicmap.openmc.net/?world=maparts&renderer=basic&zoom=0&x=-129&z=-129) nutzen, um einen passenden Plot zu finden.
|||

### Plots verbinden
Du kannst bis zu neun Plots miteinander verbinden, um bis zu 5x5 Maps umfassende MapArts zu erstellen.

Erwerbe dazu zuerst zwei oder mehr nebeneinanderliegende Plots. Stelle dich anschließend auf einen Plot, schaue in Richtung des zweiten Plots und gebe `/plot merge` ein. Es werden 500 ✪ abgezogen.

==- Beispiel
Die verbundene Fläche kann für ein großes oder auch für mehrere kleine MapArts genutzt werden.
||| Vorher
Vier einzelne Plots für vier MapArts.
![](/images/merge1.png)
||| Nachher
Ein großes Plot für ein MapArt der Größe 3x3 oder mehrere kleinere MapArts.
![](/images/merge2.png)
|||
==-

Solltest du die Verbindung aufheben wollen, erstelle bitte ein Support-Ticket. Die Kosten für die Verlinkung werden in diesem Fall nicht erstattet.

### Plot modifizieren
Der Plot kann modifiziert werden, um das Aussehen des MapArts zu verändern oder um die Sicht auf das MapArt einzuschränken.

Nutze den Befehl `/plot components`, um das Menü zu öffnen.

==- Verfügbare Modifizierungen
!!!tip Bedrock-Entfernung auf verbundenen Plots
Wenn du Bedrock entfernst und den Plot erst später verbindest, bleibt der Bedrock nur auf dem ursprünglichen Teil entfernt und du musst erneut 50 Tsd. ✪ bezahlen. Entferne Bedrock daher immer erst, wenn du die Plots bereits auf die gewünschte Größe verbunden hast. 
!!!

- **Gras entfernen**
  - Entfernt den Grasboden des Plots. Nützlich in Verbindung mit der Entfernung des Bedrocks.
  - Achtung: Die Blöcke auf Bodenhöhe werden mit Luft überschrieben.
  - Hinweis: Vor der Verwendung sollte /fly aktiviert werden.
- **Gras einfügen**
  - Fügt den Grasboden des Plots wieder hinzu.
  - Achtung: Die Blöcke auf Bodenhöhe werden mit Grasblöcken überschrieben.
- **Bedrock entfernen**
  - Entfernt den Bedrock unter dem Plot, um transparente Maparts zu ermöglichen.
  - Preis: 50 Tsd. ✪
  - Achtung: Die Blöcke unter der Bodenhöhe werden mit Luft überschrieben.
  - Hinweis: Vor der Verwendung sollte /fly aktiviert werden.
- **Plot abschirmen**
  - Errichtet eine Wand um den Plot, um dein Mapart vor fremden Blicken zu schützen.
  - Achtung: Die letzte Reihe am Rand des Plots wird Stein überschrieben.
  - Hinweis: Wenn du lediglich den Zugang zum Plot begrenzen möchtest, reicht ein Zugangsschutz mit `/plot deny *` aus.
- **Abschirmung entfernen**
  - Entfernt die Abschirmung um den Plot.
  - Achtung: Die letzte Reihe am Rand des Plots wird Luft überschrieben.
==-

### Zugang begrenzen
Um zu verhindern, dass andere Spieler eine Karte von deinem MapArt erstellen können, kannst du einen Zugangsschutz zum Plot mit `/plot deny *` festlegen. Dieser Schutz kann sich auch nur auf einzelne Spieler beziehen. Um den Schutz wieder aufzuheben, nutze `/plot remove *`.

### Rechte vergeben
#### Spieler adden
Spieler, welche auf einem Plot mit `/plot add <spieler>` geaddet wurden, können nur auf dem Plot bauen, wenn der Plotinhaber in der Bauwelt online ist

#### Spieler trusten
Spieler, welche auf einem Plot mit `/plot trust <spieler>` getrustet wurden, können jederzeit auf dem Plot bauen.

#### Rechte entfernen
Mit dem Befehl `/plot remove <spieler>` kannst du die Rechte eines Spielers entfernen.

### Teleportation
Mithilfe von `/plot list mine` kannst du eine Liste deiner Plots anzeigen und dich per Klick direkt teleportieren.

Nutze alternativ `/plot home <ID/Alias>` oder `/plot visit <ID/Alias>`, um dich zu einem deiner Plots zu teleportieren.

Den Homepunkt auf einem Plot kannst du mit `/plot sethome` an deine aktuelle Position festlegen.

### Flags festlegen
TODO

### Plotname und Beschreibung festlegen
Mit `/plot alias set <text>` kannst du den Namen des Plots festlegen. `/plot alias remove <text>` entfernt diesen wieder.

Mit `/plot desc <beschreibung>` kannst du die Beschreibung des Plots festlegen.


---

## NoMapMaking ClaimFlag (bestehende MapArts in der Bauwelt)
Um zu verhindern, dass andere Spieler eine Karte von deinem MapArt erstellen können, kannst du die NoMapMaking ClaimFlag aktivieren. Nutze dazu den Befehl `/setclaimflag nomapmaking` auf deinem Claim.

---

## MapArts patentieren
Mit dem Befehl `/mapart` kannst du ein Menü aufrufen, in welchem du deine MapArts patentieren kannst. Dort kannst du die Karte einfach in das Feld auf der linken Seite legen und die gewünschten Funktionen auswählen. Wenn eine Funktion ausgewählt wurde, klicke auf “[Bestätigen]”  und die gewünschte Funktion wird für einen kleinen Geldbetrag aktiviert:

### Replizierbarkeit
Die Funktion “Replizieren verbieten” sorgt dafür, dass MapArts nicht mehr durch einen Kartentisch oder eine Werkbank kopiert werden können. Um diese Funktion zu aktivieren, benötigst du 2000 ✪.

### Nutzbarkeit
Die Funktion “Nutzung verbieten” sorgt dafür, dass Karten nicht mehr in Bilderrahmen gelegt werden können. Der Ersteller kann jedoch die Karte weiterhin in Rahmen legen, andere jedoch können die Karte nicht entfernen und drehen. Um diese Funktion zu aktivieren, benötigst du 1000 ✪.

![](/images/mapart_patent.png)

Wird keine der Optionen aktiviert, wird das MapArt dennoch mit dem Namen des Erstellers versehen.

Als Ersteller eines Patentes für die Map bist du in der Lage, die Verwendungszwecke der eigenen Maps besser zu steuern als bei herkömmlichen Methoden. Zudem brauchst du dein MapArt jeweils nur ein Mal zu patentieren, da du als Ersteller vom Patentschutz ausgeschlossen ist und somit mehrere Replikate mit dem Schutz erzeugen kannst.

### Informationen zu MapArts anzeigen
Mit dem `/mapinfo` Befehl kannst du Informationen zu bereits platzierten MapArts aufrufen, indem du diese ansiehst und den Befehl eingibst.