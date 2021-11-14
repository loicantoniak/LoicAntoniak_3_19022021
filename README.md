# OhMyFood !

Projet 3 de la formation OpenClassrooms "Développeur Front End".

## Objectif

L'objectif de ce projet est : **Dynamisez une page web avec des animations CSS**

## Scénario

L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée.

## Fabriqué avec

* [sass](http://materializecss.com) -  préprocesseur CSS (front-end)
* [VSCode](https://code.visualstudio.com/) - Editeur de textes

## Fonctionnalités 

#### Contenu des pages

###### Page d’accueil

- [x] Affichage de la localisation des restaurants.
- [x] Une courte présentation de l’entreprise.
- [x] Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

###### Pages de menu

- [x] 4 pages contenant chacune le menu d’un restaurant.

###### Footer

- [x] Le footer est identique sur toutes les pages.
- [x] Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

###### Header

- [x] Le header est présent sur toutes les pages.
- [x] Sur la page d’accueil, il contient le logo du site.
- [x] Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

#### Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils utilisent les animations et transitions CSS, pas de JavaScript ni de librairie.

###### Boutons

- [x] Au survol, la couleur de fond des boutons principaux s'éclaircie légèrement. L’ombre portée est plus visible.
- [x] À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

###### Page d’accueil

- [x] Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini mais doit être cohérent avec la charte graphique du site.

###### Pages de menu

- [x] À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- [x] Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

Démo live : https://loicantoniak.github.io/LoicAntoniak_3_19022021/index.html

## Compétences évaluées

- Mettre en place une structure de navigation pour un site web
- Mettre en place son environnement Front-End
- Utiliser un système de gestion de versions pour le suivi du projet et son hébergement
- Mettre en œuvre des effets CSS graphiques avancés
- Assurer la cohérence graphique d'un site web

## Auteur

* **Loïc Antoniak** _alias_ [@loicantoniak](https://github.com/loicantoniak)

## Licence 

Il s'agit d'un projet dans le cadre de la formation [Développeur Front-End](https://openclassrooms.com/fr/paths/314-developpeur-front-end) d'OpenClassrooms. Le code est librement réutilisable, mais les images / logo et tout les éléments issus de l'énoncé ne m'appartiennent pas.
