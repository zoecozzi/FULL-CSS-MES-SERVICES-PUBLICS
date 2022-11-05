# Devoir-maison-css

Le travail que j'ai réalisé est visible à l'adresse suivante : https://devoirs.rogeaux.com/zoecozzi/devoir-css/

Lors de la réalisation du design de la page internet "mon service public", j'ai dans un premier temps réalisé le footer puis le header pour enfin m'atteler à réaliser la partie principale constituée du main et du aside. C'est uniquement lorsque j'ai terminé le design pour la partie ordinateur et que j'ai réalisé le design pour la partie responsive (téléphone et tablette).

Vous trouverez ci-dessous mes différents choix pour la structuration de ma page web en version ordinateur puis mes choix pour la version responsive.

### Version ordinateur

1. Footer

  J'ai fais le choix de structurer mon footer avec un grid puis avec un grid-template-columns pour pouvoir choisir les différentes largeurs de colonnes que je souhaitais. L'utilisation de "padding" et de "margin" ainsi que de "background-color" ont été utilisés tout au long de la création du design pour avoir un rendu propre, esthétique et le plus proche de ce qui été demandé. De plus j'ai du enlever des puces présentent sur les titres des grandes parties du sites car c'était des <li> dans le code, grâce à un "list-type-style:none".
Pour la partie bleu foncé du footer j'ai utilisé un "display: flex" pour pouvoir justifier tout son contenu au centre de celui-ci grâce à un "justify-content: center".
  
2. Header
  
  En ce qui concerne la partie Header, je l'ai structuré avec un "display: flex" puis avec un "justify-content: space-between" afin que les éléments se répartissent bien sur toute la largeur de l'écran. De plus j'ai rajouté un "align-items: center" afin que ma barre de recherche soit aligné au centre verticalement dans le header.
  
3. Nav
  
  La partie Nav donc la partie qui concerne le menu n'a pas été facile à réaliser. En effet, il fallait faire apparaître de l'espace entre chaque partie du menu avec un dégradé de couleur pour le fond du menu. Il y avait pleins de spécificités à ne pas oublier. Pour les grandes parties du menu, j'ai utilisé un "display: flex" pour bien les positionner puis pour le sous-menu donc les différents menus déroulant j'ai utilisé un "display: block".
  
4. Main & Aside
  
  Enfin, pour la partie principale du site internet, j'ai utilisé la mise en page de bootstrap avec les colonnes. L'utilisation de la propriété "border-radius" a été utilisée un peu partout sur la page internet afin d'arrondir les angles des différents blocks.
  
 ### Version mobile et tablette 
  
  J'ai fait le choix d'utiliser 3 médias querys principales. La première pour la partie téléphone, la deuxième pour la partie tablette et la troisième pour la partie ordinateur, mais celle m'a été utile uniquement pour une propriété. 
  
  En ce qui concerne le responsive pour le téléphone, j'ai dû changer des flex-directions pour pouvoir m'adapter à la taille de l'écran ou bien changer le display. Pour la partie gérer par bootstrap j'ai dans un premier temps essayer d'utiliser "col-sm" qui est la propriété spécifique de Bootstrap pour le responsive, mais celle-ci n'a pas fonctionné don j'ai joué avec les "width" pour que les colonnes prennent toute la largeur de l'écran et se disposent bien sur la page internet. 
  J'ai fait de même pour le reponsive spécifique aux tablettes sachant qu'une fois le responsive réalisé pour les téléphones il n'y a que très peu de propriétés à modifier pour la partie tablettes.
