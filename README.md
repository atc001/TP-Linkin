
Dans chaque balise html (exemple: <section>, <div>, <footer>...), on peut rajouter une classe comme ceci (exemple: <section class="">, <div class="">...)

Pour avoir un exemple charger le fichier exemple.html

Parametres a connaitre :

    Changer la couleur de fond de l'element, ajoutez dans class :

        -back_one : noir
        -back_two : gris claire
        -back_three : bleu clair

    Changer la disposition des elements, ajoutez dans class :

        -flex(A rajouter tout le temps, il est juste la pour activer la fonction de disposition)

        -justify_center : pour centrer verticalement les elements
        -justify_around : pour repartir l'espace restant equitablement de chaque cote des elements (exemple : xx Element xx Element xx)
        -justify_between : pour repartir l'espace restant equitablement au milieu des elements (exemple : Element xx Element xx Element)

        -items_center : pour centre horizontalement les elements

        -direction_column : pour que les elements se mettent les uns en dessous des autres
        -direction_column_rev : pareil que le precedent mais en inversant le sens
        -direction_row : pour que les elements se mettent les uns a la suite des autre
        -direction_row_reverse : pareil que le precedent mais en inversant le sens

    Changer la taille de la police :

        -small : pour petit
        -medium : pour moyen
        -big : pour gros

    Ajout d'un slider, responsive :

        Pour ajouter les images, allez dans tout en bas dans le code index.html, et insérez vos images dans les balises img situer dans la div avec l'id "partie_trois".

    Ajout d'un menu deroulant :

        Pour ajouter le menu placer regarder dans la balise header, vous y trouverez un "h4" suivi de plusieurs "li", le "h4" represente le bouton et les "li" qui representeront le menu que se devoile en cliquant sur le bouton.


    Pour ajouter des images :

        Elles doivent avoir une taille fixe : 
            -Header : 500x500
            -Album : 250x250
            -Interview : Comme vous voulez

    Bug : -Le slider bug quand on va au dela de la 4eme image sur la droite. Du cote gauche tout marche infiniment mais pas a droite.
           J'ai néanmoins réaliser le slider responsive avec la bonne disposition des elements.
          -La marge (droite et gauche) autour du header n'est pas concervée autour de la page.(résolu en mettant une width de 100% a mon header).
          -L'image de la section interview se déforme un peu suivant la largeur de la fenêtre. (résolu. j'ai place l'img dans une div et j'ai mis une width de 100% et une height en auto).

    

