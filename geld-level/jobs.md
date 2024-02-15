---
label: Jobs
layout: default
order: 599
icon: briefcase
---

# Jobs

[!badge :white_check_mark: Ingame-Tutorial verfügbar: `/warp tutorial_jobs`]

Mit Jobs kannst du während des Farmens von Items & Ausführen von alltäglichen Aktivitäten ganz einfach passiv oder aktiv Geld verdienen.\
Jobs sind nur in der Bau- und Farmwelt verfügbar.

---

## Job annehmen
Öffne das Job-Menü mit `/jobs browse` und klicke mit der rechten Maustaste auf einen Job, um ihn anzunehmen. Wie viele Jobs du gleichzeitig annehmen kannst, kannst du der folgenden Tabelle entnehmen:

{.compact}
Feature                     | Spieler | Siedler | VIP   | VIS   | + Upgrade | Champion
:---:                       | :---:   | :---:   | :---: | :---: | :---:     | :---:
Jobs¹                       | 1       | 2       | 3     | 3     |           | 3

¹ Auch beim Wechsel auf einen niedrigeren Rang bleiben bereits angenommene Jobs erhalten, können aber nicht mehr gewechselt werden.

Alle erreichten Joblevel werden beim Verlassen des Jobs gespeichert und können jederzeit weiter gesammelt werden. Das maximale Level pro Job liegt bei 200.

### Verfügbare Jobs
Job         | Tätigkeit                             | Aktionslimit (je 5s)
---         | ---                                   | ---
Holzfäller  | Fällen und Pflanzen von Bäumen        | 25
Miner	    | Abbauen von Mineralien und Erzen      | 50
Baumeister	| Platzieren von Blöcken                | 20
Buddler	    | Abbauen von Sand, Erde, Kies, etc.    | 50
Bauer	    | Felder bestellen und Zucht von Tieren | 25
Jäger	    | Töten von Tieren und Monstern         | 10
Fischer	    | Angeln von Fischen                    | 3
Braumeister	| Brauen von Tränken                    | 2

---

## Aktionslimit
Um ein Gleichgewicht im Jobsystem zu wahren und Missbrauch vorzubeugen, gibt es ein Aktionslimit für jeden Job. Dieses beschreibt die höchstmögliche Anzahl an Aktionen, mit denen man im 5-Sekunden-Takt Geld verdienen kann. Tötet man im Job Jäger innerhalb von 5 Sekunden beispielsweise 100 Mobs, so wird man nur für die ersten 10 bezahlt. Somit wollen wir das Ausnutzen großer Farmkomplexe verhindern und damit einer stetigen Inflation oder einer konstanten Nachjustierung der Erträge ausweichen.

---

## Verdienstkurve
Die Verdienstkurve gibt an, wieviel du pro Level in deinem Job verdienst.

-![](/images/job-verdienstkurve.png)

Der Wert der y-Achse (senkrechte Achse) gibt dabei den Faktor des Verdienstes an. Der Faktor gibt an, mit welchem Wert der Standardverdienst (auf Level 1) auf einem spezifischen Level multipliziert wird. Er kann nur zwischen 0 und 1 sein.

Das bedeutet, dass man am Anfang eines Jobs am meisten verdient. Gegen Level 28 in etwa beträgt der Faktor 0.2 (daher ist der Verdienst etwa 1/5 vom Start). Auf Level 50 etwa beträgt der Faktor dann wieder 0.5 (daher ist der Verdienst etwa ½ vom Start).

Der Wert der x-Achse (horizontale Achse) gibt bei der orangenen Kurve die Spielstunden im Job und bei der blauen Kurve das Level des Jobs an.

[!file Grafik in voller Größe](/images/job-verdienstkurve_large.png)

---

## Befehle
`/jobs browse`\
Öffnet das Hauptmenü, wo du Jobs anzeigen, annehmen und verlassen kannst.

`/jobs join <jobname>`\
Mit diesem Befehl kannst du direkt einen spezifischen Job annehmen.

`/jobs leave <jobname>`\
Mit diesem Befehl kannst du direkt einen spezifischen Job verlassen.

`/jobs leaveall`\
Mit diesem Befehl kannst du alle angenommenen Jobs verlassen.

`/jobs stats`\
Zeigt dein aktuelles Job-Level und die gesammelten XP an.

`/jobs info <jobname>`\
Zeigt an, wie viel Geld und XP du für die farmbaren Items des angegebenen Jobs bekommt.

`/jobs archive`\
Zeigt die bereits verlassenen, gespeicherten Jobs mit dem vorhandenen Level an.

`/jobs gtop`\
Zeigt die Top 15 aller Spieler in allen verfügbaren Jobs an.

`/jobs top <jobname>`\
Zeigt die Top 15 aller Spieler in dem angegebenen Job an.

`/jobs clearownership`\
Entfernt alle aktuell besetzten Öfen und Braustände.