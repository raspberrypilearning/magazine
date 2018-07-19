## Spalten erstellen

Webseiten verwenden oft mehrere Spalten. Lass uns ein Zwei-Spalten-Layout für deine Zeitschrift erstellen.

+ Als erstes müssen wir zwei Spalten mit `div` erstellen.
    
    Füge nun den markierten HTML-Code in der Datei `index.html` hinzu:
    
    ![screenshot](images/magazine-columns.png)

+ Gestalte die Spalten-div's so, dass eine nach links und die andere nach rechts fliesst.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Jede Spalte ist kleiner als 50%, so dass Platz für den Zwischenraum bleibt.
    
    Um die Wirkung zu sehen, musst du etwas in die Spalten schreiben.

+ Setzen wir das Bild von einem Kätzchen oben in die zweite Spalte.
    
    ![screenshot](images/magazine-kitten.png)
    
    Wie du siehst, nimmt das Bild des Kätzchens ungefähr die Hälfte der Seite in der zweiten Spalte ein.
    
    Aber es ist etwas zu gross!

+ Damit das Bild an den vorhandenen Platz angepasst wird, müssen wir `max-width:` verwenden.
    
    Füge folgenden Stil in `style.css` hinzu.
    
    ![screenshot](images/magazine-img-width.png)
    
    This will apply to all images you use in your magazine, not just the kitten.

+ Now add a class `photo` to the image so that you can style it:
    
    ![screenshot](images/magazine-photo.png)

+ And style the image to add a shadow and a twist to make the photo pop out of the page:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Make some changes until you like the result.