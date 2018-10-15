## Tworzenie kolumn

Witryny często używają wielu kolumn. Stwórzmy układ dwóch kolumn dla Twojego czasopisma.

+ Najpierw utwórz dwie kolumny `div`s.
    
    Dodaj podświetlony kod HTML do `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ Teraz ustaw kolumny divs tak, aby jeden unosił się na lewo, a drugi na prawo.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Każda kolumna jest mniejsza niż 50%, więc jest miejsce na wypełnienie.
    
    Aby zobaczyć efekt, musisz dodać coś do kolumny.

+ Dodajmy obrazek kotka na szczyt kolumny 2.
    
    ![screenshot](images/magazine-kitten.png)
    
    Zwróć uwagę, że obraz kociaka jest umieszczony w połowie długości strony w drugiej kolumnie.
    
    Jest jednak trochę duże!

+ Użyjmy `max-width:`, aby dopasować obrazy do ich ramki.
    
    Dodaj następujący styl do `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    Będzie on dotyczył wszystkich zdjęć, których używasz w swoim czasopiśmie, a nie tylko kociaka.

+ Teraz dodaj `photo` do obrazka, aby móc je stylizować:
    
    ![screenshot](images/magazine-photo.png)

+ Wystylizuj obraz, aby dodać cień i twist, aby zdjęcie wyróżniało się na tle strony:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Wprowadzaj zmiany, dopóki nie polubisz wyniku.