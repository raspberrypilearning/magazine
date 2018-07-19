## Spalten erstellen

Webseiten verwenden oft mehrere Spalten. Lass uns ein Zwei-Spalten-Layout für deine Zeitschrift erstellen.

+ Als erstes müssen wir zwei Spalten mit `div` erstellen.
    
    Füge nun den markierten HTML-Code in der Datei `index.html` hinzu:
    
    ![Screenshot](images/magazine-columns.png)

+ Gestalte die Spalten-div's so, dass eine nach links und die andere nach rechts fliesst.
    
    ![Screenshot](images/magazine-columns-style.png)
    
    Jede Spalte ist kleiner als 50%, so dass Platz für den Zwischenraum bleibt.
    
    Um die Wirkung zu sehen, musst du etwas in die Spalten schreiben.

+ Setzen wir das Bild von einem Kätzchen oben in die zweite Spalte.
    
    ![Screenshot](images/magazine-kitten.png)
    
    Wie du siehst, nimmt das Bild des Kätzchens ungefähr die Hälfte der Seite in der zweiten Spalte ein.
    
    Aber es ist etwas zu gross!

+ Damit das Bild an den vorhandenen Platz angepasst wird, müssen wir `max-width:` verwenden.
    
    Füge folgenden Stil in `style.css` hinzu.
    
    ![Screenshot](images/magazine-img-width.png)
    
    Dies gilt für alle Bilder, die du in deiner Zeitschrift benutzt, nicht nur für das des Kätzchens.

+ Füge jetzt eine Klasse namens `photo` zum Bild hinzu, damit du es grafisch gestalten kannst:
    
    ![Screenshot](images/magazine-photo.png)

+ Und gestalte das Aussehen des Bildes so, dass es einen Schatten wirft, und drehe es etwas, damit es aussieht als ob es aus der Seite herausspringt:
    
    ![Screenshot](images/magazine-photo-style.png)
    
    Ändere die Parameter, bis du mit dem Ergebnis zufrieden bist.