## Kreiranje stupaca

Na veb-stranicama često se koristi više stupaca. Napravimo raspored u dva stupca za tvoj časopis.

+ Prvo kreiraj dva `div` za stupce.
    
    Dodaj označeni HTML u `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ Sada stilizuj oba div za stupce tako da jedan pluta ulijevo, a drugi udesno.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Svaki stubac zauzima manje od 50%, tako da ima prostora za popunu.
    
    Biće potrebno da nešto dodaš u stubac da bismo vidjeli rezultat.

+ Dodajmo sliku mačeta na vrh stupca 2.
    
    ![screenshot](images/magazine-kitten.png)
    
    Obrati pažnju da je slika mačeta pozicionirana otprilike na sredini stranice, u drugom stupcu.
    
    Izgleda, ipak, da je slika veća nego što bi trebalo!

+ Upotrijebimo `max-width:` kako bi se slike uklopile u svoj kontejner.
    
    Dodaj sljedeći stil u `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    Ovaj stil će se primijenjivati na sve slike koje koristiš u svom časopisu, ne samo na sliku mačeta.

+ Sada slici dodaj klasu `photo` kako bismo mogli da je stilizujemo:
    
    ![screenshot](images/magazine-photo.png)

+ Stilizuj sliku tako što ćeš dodati sjenku (shadow) i okrenuti je tako da izgleda kao da fotografija izlazi sa stranice:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Pravi izmjene sve dok ti se ne svidi rezultat.