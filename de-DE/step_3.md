## Spalten erstellen

Webseiten verwenden oft mehrere Spalten. Lass uns ein Zwei-Spalten-Layout für deine Zeitschrift erstellen.

+ Als erstes müssen wir zwei Spalten mit `div` erstellen.
    
    Füge nun den markierten HTML-Code in der Datei `index.html` hinzu:
    
    ![screenshot](images/magazine-columns.png)

+ Gestalte die Spalten-div's so, dass eine nach links und die andere nach rechts fliesst.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Each column is less than 50% so there's room for padding.
    
    You'll need to add something to a column to see the effect.

+ Let's add a kitten picture to the top of column 2.
    
    ![screenshot](images/magazine-kitten.png)
    
    Notice that the kitten image is positioned about half-way across the page, in the second column.
    
    It's a bit big though!

+ Let's use `max-width:` to make images fit within their container.
    
    Add the following style to `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    This will apply to all images you use in your magazine, not just the kitten.

+ Now add a class `photo` to the image so that you can style it:
    
    ![screenshot](images/magazine-photo.png)

+ And style the image to add a shadow and a twist to make the photo pop out of the page:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Make some changes until you like the result.