# WorkAdventure Map Starter Kit des WAK-LAB

Dies ist ein Starter-Kit, mit dem Sie Ihre eigene Karte für 
[WorkAdventure](https://workadventu.re) erstellen können.

## Werkzeuge, die Sie benötigen

Um Ihre eigene Karte für WorkAdventure zu erstellen, benötigen Sie:

- die Software [Tiled Editor] (https://www.mapeditor.org/)
- "Kacheln" (d. h. Bilder) zum Erstellen Ihrer Karte (dieses Starter-Kit bietet ein gutes Standard-Kachelset für Büros)
- ein Webserver zur Bereitstellung Ihrer Karte (in diesem Starter-Kit wird vorgeschlagen, statische Github-Seiten als kostenlosen und leistungsfähigen Webserver zu verwenden).

## Anfangen

Auf der [Github-Repository-Seite] (https://github.com/thecodingmachine/workadventure-map-starter-kit),
Klicken Sie auf die Schaltfläche ** "Diese Vorlage verwenden" **. Sie werden aufgefordert, einen Repository-Namen für Ihre Karte einzugeben.

![](docs/create_repo.png)

Stellen Sie sicher, dass das Repository "Öffentlich" ist.

Klicken Sie in Ihrem neu erstellten Repository auf die Registerkarte ** Einstellungen ** und scrollen Sie zum Abschnitt ** GitHub-Seiten **.
Wählen Sie dann den Zweig ** gh-pages ** aus.

![](docs/github_pages.png)

Warten Sie einige Minuten, bis ein Github eine neue Website mit dem Inhalt des Repositorys bereitstellt.
Die Adresse der Website ist im Bereich "GitHub-Seiten" sichtbar.

![](docs/website_address.png)

Klick auf den Link. Sie sollten direkt zu WorkAdventure auf Ihrer Karte weitergeleitet werden!

## Anpassen Ihrer Karte

Ihre Karte ist jetzt online. Sie müssen es anpassen.

### Klonen der Karte

Beginnen Sie mit dem Klonen der Karte. Wenn Sie an Git und GitHub gewöhnt sind, klonen Sie einfach die Karte
mit Ihrem bevorzugten Werkzeug auf Ihren Computer und [zum nächsten Kapitel springen] (# Laden der Karte in Kacheln).

Wenn Sie Git noch nicht kennen, bedeutet das Klonen der Karte, dass Sie die Karte auf Ihren Computer herunterladen.
Dazu benötigen Sie Git oder ein Git-kompatibles Tool. Unser Rat ist zu verwenden
[GitHub Desktop](https://desktop.github.com/).

TODO: testen und fortfahren

### Laden der Karte in Tiled

Die Beispielkarte befindet sich in der Datei "map.json".
Sie können diese Datei in [Kacheln] (https://www.mapeditor.org/) laden.

Jetzt liegt es an Ihnen, die Karte zu bearbeiten und Ihre eigene Karte zu schreiben.

Einige Ressourcen zu Tiled:

- [Gekachelte Dokumentation] (https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled Video Tutorials] (https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### Über WorkAdventu.re-Karten

Um eine Karte zu entwerfen, die von WorkAdventure gelesen werden kann, müssen Sie einige Einschränkungen beachten.

Insbesondere müssen Sie:

- Legen Sie eine Startposition für die Spieler fest
- Konfigurieren Sie die "Bodenebene" (damit WorkAdventure Zeichen über dem Boden, aber unter der Decke korrekt anzeigen kann).
- Schließlich können Sie Ausgänge platzieren, die auf andere Karten verweisen

All dies wird in der [WorkAdventure-Dokumentation] (https://github.com/thecodingmachine/workadventure/#designing-a-map) beschrieben.
Bitte probieren Sie es unbedingt aus.

### Karte verschieben

Wenn Ihre Änderungen fertig sind, müssen Sie die Änderungen "festschreiben" und "zurückschieben" an GitHub.
Warten Sie einfach ein paar Minuten, und Ihre Karte wird automatisch an den Webserver der GitHub-Seiten weitergegeben.


### Karte hochladen
git add .
git commit -m "Meine neue Karte"
git push

TODO:
Mehr zu diesem Ausgangstext
Für weitere Übersetzungsinformationen ist ein Ausgangstext erforderlich
Feedback geben
Seitenleisten
