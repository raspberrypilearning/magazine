## Vytváření sloupců

Webové stránky často používají více sloupců. Pojďme vytvořit dvousloupcové rozložení pro tvůj časopis.

+ Nejprve vytvoř dva elementy `div` pro sloupce.
    
    Přidej zvýrazněný HTML kód do `index.html`:
    
    ![snímek obrazovky](images/magazine-columns.png)

+ Nyní nastylizuj elementy div tak, aby jeden měl vlastnost float: left a druhý float: right.
    
    ![snímek obrazovky](images/magazine-columns-style.png)
    
    Každý sloupec je menší než 50%, máme tedy místo pro padding.
    
    Pro zobrazení výsledku musíš něco vložit do sloupce.

+ Pojďme přidat obrázek koťátka na začátek druhého sloupce.
    
    ![snímek obrazovky](images/magazine-kitten.png)
    
    Povšimni si, že obrázek koťátka je umístěn v polovině stránky v druhém sloupci.
    
    Je ale dost velký!

+ Zkusme použít `max-width:`, aby se mohly obrázky vejít do svého kontejneru.
    
    Přidej následující styl do `style.css`.
    
    ![snímek obrazovky](images/magazine-img-width.png)
    
    Tento styl bude použit na všechny obrázky v časopisu, a ne jenom na koťátko.

+ Nyní přidej obrázku třídu `photo`, poté jej budeš moci nastylizovat:
    
    ![snímek obrazovky](images/magazine-photo.png)

+ Nyní nastylizuj obrázek - přidej stín a natoč ho, aby obrázek ze stránky vyčníval:
    
    ![snímek obrazovky](images/magazine-photo-style.png)
    
    Udělej nějaké změny, než budeš s výsledkem spokojený.