## Vytváření sloupců

Webové stránky často používají více sloupců. Pojďme vytvořit dvousloupcové rozložení pro tvůj časopis.

+ Nejprve vytvoř elementy `div` pro dva sloupce.
    
    Přidej zvýrazněný HTML kód do `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ Nyní nastylizuj elementy div tak, aby jeden měl vlastnost float: left a druhý float: right.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Každý sloupec je menší než 50%, tudíž tu je místo pro padding.
    
    Pro zobrazení výsledku musíš něco vložit do sloupce.

+ Pojďme přidat obrázek koťátka na začátek sloupce 2.
    
    ![screenshot](images/magazine-kitten.png)
    
    Povšimni si, že obrázek koťátka je umístěn v polovině stránky v sloupci druhém.
    
    Je ale docela velký!

+ Zkusme použít `max-width:`, aby se mohly obrázky vejít do svého kontejneru.
    
    Přidej následující styl do `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    Tohle bude použito na všechny obrázky, které vložíš do časopisu, a ne jenom na koťátko.

+ Nyní přidej obrázku třídu `photo`, poté jej budeš moci nastylizovat:
    
    ![screenshot](images/magazine-photo.png)

+ Nyní nastylizuj obrázek - přidej stín a natoč ho, aby obrázek ze stránky vyčníval:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Udělej nějaké změny, než se ti výsledek začne líbit.