# Utilisation des classes 

## Structure de l'infographie

Une infographie est constituée de plusieurs blocs. Chaque bloc contient un titre, et un ou plusieurs items. 

### Blocs
Les **blocs** se positionnent les uns à coté des autres et/ou les les uns en dessous des autres. 
Pour définir la taille d'un bloc, on utilisera les classes suivantes : 
* b3-3 : bloc de 3/3 soit 100% de la largeur
* b2-3 : bloc de 2/3 soit 66% de la largeur
* b1-2 : bloc de 1/2 soit 50% de la largeur
* b1-3 : bloc de 1/3 soit 33% de la largeur
        
        `<div class="b3-3"> Bloc de 3/3 
        </div>`
        
### Titres
Les **titres** se positionnent à l'intérieur des blocs en utilisant les balises `<h1>` à `<h6>` pour marquer leur importance syntaxique. Pour définir en plus la largeur du titre (indépendante de son niveau hiérarchique), on utilise la même logique que pour les blocs : 
* t3-3 : titre de 3/3 soit 100% de la largeur
* t2-3 : titre de 2/3 soit 66% de la largeur
* t1-2 : titre de 1/2 soit 50% de la largeur
* t1-3 : titre de 1/3 soit 33% de la largeur
    
     `<div class="b3-3">
            <h1 class="t3-3">Titre de 3/3</h1> 
        </div>`

### Items  
Enfin, les **items** sont des éléments positionés à l'intérieur des blocs. Un bloc de 100% de large pourra ainsi contenir 1, 2 ou 3 items. Pour définir la taille d'un item, on utilisera les classes suivantes : 
* i3-3 : item de 3/3 soit 100% de la largeur
* i2-3 : item de 2/3 soit 66% de la largeur
* i1-2 : item de 1/2 soit 50% de la largeur
* i1-3 : item de 1/3 soit 33% de la largeur

        `<div class="b3-3">
            <h1 class="t3-3">Titre de 3/3</h1> 
                <div class="i1-3"> Item 1 </div>
                <div class="i1-3"> Item 2 </div>
                <div class="i1-3"> Item 3 </div>
        </div>`
        
## Hauteur des blocs
Pour obtenir un alignement haut et bas harmonieux, il peut être nécessaire de forcer les blocs ou les items à prendre une hauteur particulière s'ils n'ont pas des éléments de la même hauteur.
Il est possible de forcer les hauteurs suivantes : 
* haut50
* haut100
* haut150
* haut200
* haut250
* haut280
* haut300

## Alignement

les blocs peuvent être alignés en haut, au milieu ou en bas en utilisant les classes correspondantes : 
* alignhaut
* alignmilieu
* alignbas

il est également possible de les faire flotter :
* flottegauche
* flottedroit

## Couleurs

### Couleurs des éléments de structure
Il est possible de définit une couleur de fond sur les éléments de structure : bloc, titre et item
Il suffit d'ajouter la classe correspondante : 
* blanc : fond blanc, texte noir 
* rouge : fond rouge, texte blanc 
* orange : fond blanc, texte blanc  
* bleu : fond bleu, texte blanc  
* bleufoncé : fond bleu foncé, texte blanc  
* violet : fond violet, texte blanc   

`<div class="b3-3 rouge"> Bloc avec un fond rouge </div>`

### Couleurs de texte

Il est possible de modifier la couleur de la police par les classes : 

* texterouge
* texteorange
* textebleu
* textebleufonce
* texteviolet
* textevert



## Taille de texte

Il est possble d'augmenter la taille du texte à l'aide des classes appropriées : 
* taille1 : taille normale (1em)
* taille2 : facteur 1.2
* taille3 : facteur 1.6
* taille4 : facteur 2.2
* taille5 : facteur 2.8

## Typographie

Quelques classes pour modifier la typographie : 

* gras : graisse la fonte
* majuscule : mise en capitale

## Paragraphes

Quelques classes pour modifier les styles de paragraphes : 

* lignehaute : hauteur de ligne augmentée (1.4)
* lignereduite : hauteur de ligne réduite (0.8)
* grossemarge : bloc à 70% avec marge auto à droite et gauche

## Bouttons
* boutonclic : Bouton clicable (ajouter une couleur de bloc)

## Hacks

* inline : donne un comportement `inline` a un bloc
* titre haut : ajout d'un padding de 20 px en haut
* clear : annule les flottants
