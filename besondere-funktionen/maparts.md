---
label: Maparts
layout: default
order: 394
icon: image

---

# Maparts

Mit Maparts kannst du die gestalterischen Möglichkeiten in Minecraft erweitern und deiner Kreativität freien Lauf lassen.

## Erbauen von Maparts
Auf OpenMC können Maparts in einer separaten Flachwelt erbaut werden. Diese Welt besitzt der Mapgröße entsprechende Grundstücke ("Plots").

[!badge size="xl" text=":cyclone: Zur Welt: **/warp Bauwelt-Maparts**"]

Jeder Plot ist 132x132 Blöcke groß: 128x128 Blöcke für das MapArt sowie zwei Blöcke als Puffer für die nördliche Reihe sowie die optionale Abschirmung.

Aktuell kannst du maximal 30 Plots gleichzeitig beanspruchen. Zukünftig kannst du die maximale Anzahl erhöhen, diese Möglichkeit wird demnächst zur Verfügung stehen.

!!!success Richtlinien für die Nutzung der Mapart-Welt
- Die Plots in der MapArt-Welt dürfen ausschließlich für Maparts genutzt werden. Es dürfen nur Items, die für den MapArt-Bau benötigt werden, dort gelagert werden.
- Plot-Modifikationen sind aus Gründen der Performance sparsam zu verwenden. Das zu häufige Aktivieren und Deaktivieren von Modifikationen ist daher zu unterlassen.
- Blöcke, welche durch die Plot-Modifikationen auf dem Plot erscheinen, dürfen nicht abgefarmt werden.
!!!

### Plot beanspruchen
Um einen Plot zu beanspruchen und darauf zu bauen, gibt es zwei Möglichkeiten:

||| :one: Automatische Beanspruchung
Gebe `/plot auto` ein, um einen freien Plot zu beanspruchen.\
Es werden 500 ✪ abgezogen.

**Achtung:** Wenn du ein größeres MapArt erstellen möchtest, nutze stattdessen die manuelle Beanspruchung.
||| :two: Manuelle Beanspruchung
Fliege zu einem freien Plot und gebe `/plot claim` ein.\
Es werden 500 ✪ abgezogen.

**Tipp:** Du kannst die [Basis-Livemap](https://basicmap.openmc.net/?world=Maparts&renderer=basic&zoom=0&x=-129&z=-129) nutzen, um einen passenden Plot zu finden.
|||

### Plots verbinden
Du kannst bis zu neun Plots miteinander verbinden, um bis zu 5x5 Maps umfassende Maparts zu erstellen.

Erwerbe dazu zuerst zwei oder mehr nebeneinanderliegende Plots. Stelle dich anschließend auf einen Plot, schaue in Richtung des zweiten Plots und gebe `/plot merge` ein. Es werden 500 ✪ abgezogen.

==- Beispiel
Die verbundene Fläche kann für ein großes oder auch für mehrere kleine Maparts genutzt werden.
||| Vorher
Vier einzelne Plots für vier 1x1 große Maparts.
![](/images/merge1.png)
||| Nachher
Ein großes Plot für ein MapArt der Größe 3x3 oder mehrere kleinere Maparts.
![](/images/merge2.png)
|||
==-

Solltest du die Verbindung aufheben wollen, erstelle bitte ein Support-Ticket. Die Kosten für die Verlinkung werden in diesem Fall nicht erstattet.

### Plot modifizieren
Der Plot kann modifiziert werden, um das Aussehen des Maparts zu verändern oder um die Sicht auf das MapArt einzuschränken.

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
  - Errichtet eine Wand mit Dach um den Plot, um dein Mapart vor fremden Blicken zu schützen.
  - Achtung: Die letzte Reihe am Rand des Plots wird mit Stein überschrieben.
  - Hinweis: Wenn du lediglich den Zugang zum Plot begrenzen möchtest, reicht ein Zugangsschutz mit `/plot deny *` aus.
- **Abschirmung entfernen**
  - Entfernt die Abschirmung um den Plot.
  - Achtung: Die letzte Reihe am Rand des Plots wird mit Luft überschrieben.
==-

### Zugang begrenzen
Um zu verhindern, dass andere Spieler eine Karte von deinem MapArt erstellen können, kannst du einen Zugangsschutz zum Plot mit `/plot deny *` festlegen. Dieser Schutz kann sich auch nur auf einzelne Spieler beziehen. Um den Schutz wieder aufzuheben, nutze `/plot remove *`.

### Rechte vergeben
#### Spieler adden
Spieler, welche auf einem Plot mit `/plot add <spieler>` geaddet wurden, können nur auf dem Plot bauen, wenn der Plotinhaber in der Bauwelt online ist.

#### Spieler trusten
Spieler, welche auf einem Plot mit `/plot trust <spieler>` getrustet wurden, können jederzeit auf dem Plot bauen.

#### Rechte entfernen
Mit dem Befehl `/plot remove <spieler>` kannst du die Rechte eines Spielers entfernen.

### Teleportation
Mithilfe von `/plot list mine` kannst du eine Liste deiner Plots anzeigen und dich per Klick direkt teleportieren.

Nutze alternativ `/plot home <ID/Alias>` oder `/plot visit <ID/Alias>`, um dich zu einem deiner Plots zu teleportieren.

Den Homepunkt auf einem Plot kannst du mit `/plot sethome` an deine aktuelle Position festlegen.

### Flags festlegen
Du kannst verschiedene Flags auf dem Plot festlegen. Die Flags sind unabhängig von den ClaimFlags und ohne Freischaltung nutzbar.

Nutze den Befehl `/plot flag add <flag> <true/false>` zum aktivieren oder deaktivieren.

Flag          | Beschreibung                  | Standard
:---:         | :---:                         | :---:
coral-dry     | Trocknen von Korallen         | False
crop-grow     | Wachsen von Pflanzen          | True
copper-oxide  | Oxidieren von Kupfer          | False
grass-grow    | Wachsen von Gras              | True
ice-melt      | Schmelzen von Eis             | False
(leaf-decay)  | Verfall von Blättern          | Dauerhaft in der Mapart-Welt deaktiviert
mycel-grow    | Wachsen von Myzel             | True
snow-melt     | Schmelzen von Schnee          | True
soil-dry      | Austrocknen von Erde          | False
vine-grow     | Wachsen von Ranken            | True


### Plotname und Beschreibung festlegen
Mit `/plot alias set <text>` kannst du den Namen des Plots festlegen. `/plot alias remove <text>` entfernt diesen wieder.

Mit `/plot desc <beschreibung>` kannst du die Beschreibung des Plots festlegen.

---

## NoMapMaking ClaimFlag (bestehende Maparts in der Bauwelt)
Um zu verhindern, dass andere Spieler eine Karte von deinem MapArt erstellen können, kannst du die NoMapMaking ClaimFlag aktivieren. Nutze dazu den Befehl `/setclaimflag nomapmaking` auf deinem Claim.

---

## Maparts patentieren
Mit dem Befehl `/mapart` kannst du ein Menü aufrufen, in welchem du deine Maparts patentieren kannst. Dort kannst du die Karte einfach in das Feld auf der linken Seite legen und die gewünschten Funktionen auswählen. Wenn eine Funktion ausgewählt wurde, klicke auf “[Bestätigen]”  und die gewünschte Funktion wird für einen kleinen Geldbetrag aktiviert:

### Replizierbarkeit
Die Funktion “Replizieren verbieten” sorgt dafür, dass Maparts nicht mehr durch einen Kartentisch oder eine Werkbank kopiert werden können. Um diese Funktion zu aktivieren, benötigst du 2000 ✪.

### Nutzbarkeit
Die Funktion “Nutzung verbieten” sorgt dafür, dass Karten nicht mehr in Bilderrahmen gelegt werden können. Der Ersteller kann jedoch die Karte weiterhin in Rahmen legen, andere jedoch können die Karte nicht entfernen und drehen. Um diese Funktion zu aktivieren, benötigst du 1000 ✪.

![](/images/mapart_patent.png)

Wird keine der Optionen aktiviert, wird das MapArt dennoch mit dem Namen des Erstellers versehen.

Als Ersteller eines Patentes für die Map bist du in der Lage, die Verwendungszwecke der eigenen Maps besser zu steuern als bei herkömmlichen Methoden. Zudem brauchst du dein MapArt jeweils nur ein Mal zu patentieren, da du als Ersteller vom Patentschutz ausgeschlossen ist und somit mehrere Replikate mit dem Schutz erzeugen kannst.

### Informationen zu Maparts anzeigen
Mit dem `/mapinfo` Befehl kannst du Informationen zu bereits platzierten Maparts aufrufen, indem du diese ansiehst und den Befehl eingibst.