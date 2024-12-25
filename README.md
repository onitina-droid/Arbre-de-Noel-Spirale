Arbre de Noël Interactif 🎄✨
===============

J'ai trouver cet arbre sur github :

![github](https://anvaka.github.io/atree/)


Bienvenue dans le projet Arbre de Noël Interactif ! Ce projet est basé sur un code original pour des spirales animées, auquel ont été ajoutées des fonctionnalités supplémentaires, notamment une étoile au sommet du sapin et un texte festif. Le tout est créé avec HTML et JavaScript.

🚀 Ce projet est basé sur le code original pour des spirales qui ont été utilisées pour construire l'arbre de Noël.

# 🎁 Fonctionnalités principales :
Spirales animées : Un ensemble de spirales tournantes ornent le sapin de Noël, avec des couleurs vives qui apportent une touche magique à la scène.
Étoile scintillante : Une étoile en forme de triangles, dessinée en haut du sapin, ajoutant une finition brillante à l'arbre.
Texte Festif : Le texte "Joyeux Noël la coloc" apparaît en bas de l'écran dans une police de Noël élégante, avec un dégradé de couleurs festives (rouge et vert) et un contour doré.
Interaction dynamique : Cliquez sur le texte pour déclencher un magnifique feu d'artifice virtuel sur l'écran.

# 🎨 Technologies utilisées :
HTML5 : Structure de la page et balisage.
CSS3
JavaScript : Animations interactives, génération des spirales, de l'étoile et du texte, ainsi que la gestion des interactions avec l'utilisateur.

# 🔧 Structure du projet :
Le projet utilise principalement deux fichiers :

index.html : La structure de base de la page, qui contient le canevas pour afficher les animations.
script.js : Le fichier JavaScript, qui gère la logique des animations, des spirales, de l'étoile, du texte festif, et des interactions utilisateur.

# 📦 Installation :
Clonez le dépôt sur votre machine locale :

bash
Copy code
git clone <URL du dépôt>
Ouvrez le fichier index.html dans votre navigateur préféré pour voir l'animation en action.

# 🔥 Fonctionnalité de l'animation :
Une fois la page ouverte, le sapin de Noël commence à tourner avec des spirales colorées.
Le texte festif apparaît en bas avec des effets de couleur et de contour.
En cliquant sur le texte, vous déclencherez un feu d'artifice virtuel qui ajoutera encore plus de magie à l'expérience.

# 🌟 Contribuer :
Les contributions sont les bienvenues ! Si vous avez des idées pour améliorer ce projet ou si vous voulez partager vos propres créations de Noël, n'hésitez pas à ouvrir un issue ou à envoyer une pull request.


# 📜 Détails sur la création du projet :
Ce projet est une évolution d'un code de spirales animées, créé initialement pour représenter des spirales en mouvement. Le sapin de Noël est construit à partir de deux spirales, comme décrit dans ces 11 lignes de code, avec des ajouts pour personnaliser le projet.

# Les ajouts incluent :

Une étoile au sommet du sapin : Ajoutée en haut du sapin pour renforcer l'aspect festif, dessinée avec des triangles pour créer l'effet d'une étoile lumineuse.
Un texte festif : Le texte "Joyeux Noël la coloc" apparaît au bas de l'écran, avec un dégradé de couleurs de Noël et un contour doré pour un effet visuel raffiné.
Une autre spirale doree pour ajouter l'effet festif

Interaction avec l'utilisateur : Le texte est interactif : lorsqu'il est cliqué, un feu d'artifice est déclenché pour ajouter de la magie à l'expérience.
Le projet se compose d'un canevas HTML5 qui sert de toile de fond pour dessiner les animations et interagir avec l'utilisateur à travers JavaScript.

C:\Users\ic\Documents\Dev Oni\NOEL_CODE













How it's built?
---------------
The tree is built of two spirals. These [11 lines of code] render one line on spiral. It includes 3d projection and background shadow. _Almost_ the same as this [wiki image](http://en.wikipedia.org/wiki/File:ComplexSinInATimeAxe.gif):

![spiral](http://upload.wikimedia.org/wikipedia/commons/a/a5/ComplexSinInATimeAxe.gif)

It's almost perfect now
-----------------------

**EDIT:** Thank you reddit. With your help we made it almost perfect. You are awesome! 

Huge appreciation goes to [@CensoredUsername](https://github.com/CensoredUsername) who made [significant improvement](http://www.reddit.com/r/programming/comments/1tswai/t_sin_t_christmas_tree/cebhvu9). 

[@Yazuak](https://github.com/Yazuak) first gave and implemented [idea](http://www.reddit.com/r/programming/comments/1tswai/t_sin_t_christmas_tree/cebajpt) of how to manage even distribution of points along the curves.

* Vitaliy Kaurov implemented the same tree in Wolfram language... in just [15 lines of code](http://community.wolfram.com/groups/-/m/t/175891).
* [David Librera](https://github.com/davidlibrera) rewrote this in CoffeeScript. Checkout [his repository](https://github.com/davidlibrera/atree/tree/master/js/coffee) for nice OO design. 
* Chris Warren-Smith [wrote it in SmallBASIC](https://gist.github.com/chrisws/3cf97b7b7f1c2d6f9741464a2dfb3c3b)
* Mike Mallin made it [available in C](https://github.com/mremallin/christmas_tree) using SDL2 and OpenGL 3.2
* SFML port by [@deniskropp](https://github.com/deniskropp) is available here: https://github.com/deniskropp/christmas_tree


So, what's left? Just small changes which could make this tree perfect:

* Shadows are not accurate
* I think code is more complex than it should be (subjectively).

# Happy Holidays!

# license

MIT
