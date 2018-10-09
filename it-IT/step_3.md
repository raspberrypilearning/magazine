## Creazione di colonne

I siti web usano spesso più colonne. Creiamo una struttura a due colonne per la tua rivista.

+ Per prime, creaimo due colonne con il tag `div`.
    
    Aggiungi le righe di HTML evidenziate al file `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ Ora modifica le colonne per collocarne una sul lato sinistro e l'altra sul lato destro.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Ogni colonna è più piccola della metà della pagina, quindi c'è del margine esterno.
    
    Avrai bisogno di aggiungere qualcosa alla colonna per vedere l'effetto.

+ Aggiungiamo l'immagine di un gattino in cima alla seconda colonna.
    
    ![screenshot](images/magazine-kitten.png)
    
    Nota che l'immagine del gattino è posizionata a metà della pagina, nella seconda colonna.
    
    È un po' troppo grande però!

+ Usiamo `max-width:` per adeguare le dimensione delle immagini ai loro contenitori.
    
    Aggiungi quanto segue al file `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    Queste modifiche verranno applicate a tutte le immagini che userai nella tua rivista, non solo a quella del gattino.

+ Ora aggiungi una classe `photo` all'imagine per modificarne lo stile:
    
    ![screenshot](images/magazine-photo.png)

+ Modifica l'immagine per aggiungere un'ombra e un'animazione per far uscire la foto dalla pagina:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Modifica la pagina a tuo gradimento.