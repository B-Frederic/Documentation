# Exemple de découpage d'une maquette 

## **Important**
Ceci est un simple exemple, on peut le faire de différentes façons, avec des balises différentes, l'objectif la s'est juste de mieux comprendre un exemple de découpage pour ceux qui ont encore un peu de mal.

*Ne vous inquiétez pas, ça va venir avec la pratique, et pareil pour anticiper le découpage selon les propriétés que vous aurez à utiliser.*

![voir l'image](./assets/img/D%C3%A9coupage%20atelier%20entier.png)

> La div `class="container"` qui englobe toute la page, permet de pouvoir dans ce cas, utiliser la propriété `display: flex;`, qui lui permet de se mettre par défaut en ligne `row` et donc de mettre le `header` et `main` côte à côte. 

> Le `header` et le `main` permet d'avoir eux même chacun leur contenu également, et de pouvoir utiliser également les propriétés voulues dedans, comme le `display: flex;`, `position: fixed`, etc... Celà permet de gérer les éléments à l'intérieur.

> Pour l'intérieur des balises, exemple dans le `main` (la partie de droite), il vous faudra obligatoirement dans ce schéma-là, d'autre balise, exemple une balise `article` pour créer une **boite** et y mettre: `le tag` `le titre` etc...

> Comme on le voit dans la découpe, il y a également dans cette `article` jaune, une autre `div` marron, qui elle contient : `img` `pseudo` `date`. On peut anticiper en se disant qu'on va utiliser un `display: flex;` dessus pour les mettres en lignes et gérer son comportement.

Vous pouvez donc découper comme vous voulez votre maquette, pensez à bien la couper en "morceau" pour éviter de vous compliquer la vie et pour obtenir une meilleure gestion des propriétés dessus.
