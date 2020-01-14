## Creating Columns

Les sites Web utilisent souvent plusieurs colonnes. Créons une mise en page sur deux colonnes pour votre magazine.

+ Commençons pas créer deux `div`s pour les colonnes.
    
    Ajoutez le HTML en surbrillance à `index.html` :
    
    ![screenshot](images/magazine-columns.png)

+ Maintenant, stylisez les <0>div</0>s des colonnes de façon à ce que l'un flotte à gauche et l'autre à droite.
    
    ![screenshot](images/magazine-columns-style.png)
    
    Chaque colonne est inférieure à 50%, il y a donc de la place pour les remplissages.
    
    Vous aurez besoin d'ajouter quelque chose à une colonne pour voir l'effet.

+ Ajoutons une image de chaton en haut de la seconde colonne.
    
    ![screenshot](images/magazine-kitten.png)
    
    Remarquez que l'image du chaton est positionnée à peu près au milieu de la page, dans la deuxième colonne.
    
    Mais c'est un peu gros !

+ Utilisons `max-width:` pour faire tenir les images dans leur conteneur.
    
    Ajoutez le style suivant à `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    Cela s'applique à toutes les images que vous utilisez dans votre magazine, et pas seulement au chaton.

+ Ajoutons maintenant une classe `photo` à l'image pour pouvoir la styliser :
    
    ![screenshot](images/magazine-photo.png)

+ Et stylisons l'image pour ajouter une ombre et une déformation pour faire ressortir la photo de la page :
    
    ![screenshot](images/magazine-photo-style.png)
    
    Faites quelques changements jusqu'à ce que vous aimiez le résultat.