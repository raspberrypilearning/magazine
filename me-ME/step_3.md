## Kreiranje kolona

Na veb-sajtovima često se koristi više kolona. Napravimo raspored u dvije kolone za tvoj časopis.

+ Prvo kreiraj dva `div` za kolone.
    
    Dodaj označeni HTML u `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ Sada stilizuj oba div za kolone tako da jedna pluta ulijevo, a druga udesno.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Svaka kolona zauzima manje od 50%, tako da ima prostora za popunu.
    
    Biće potrebno da nešto dodaš u kolonu da bismo vidjeli rezultat.

+ Dodajmo sliku mačeta na vrh kolone 2.
    
    ![screenshot](images/magazine-kitten.png)
    
    Obrati pažnju na to da je slika mačeta postavljena otprilike na sredini stranice, u drugoj koloni.
    
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