---
layout: post
title: "Grow & Rest"
lang: fr
ref: grow-and-rest
thumbnail: grow_rest_cover.png
thumbnail-alt: Grow & Rest
description: Un god-game contemplatif réalisé en C# avec Unity pendant l'Unijam 2019
tags: perso gamejam game csharp
---

# À propos de [Grow & Rest](https://resteam.itch.io/rest-grow)

Grow & Rest est un *god-game* contemplatif, où l'on quide des "slimes" dans la construction d'édifices au travers du temps. Lorsqu'une slime atteint sa destinations, elle se solidifie, devenant une brique d'une structure plus complexe.

Les joueurs peuvent choisir de laisser les slimes faire et contempler leurs oeuvres, ou désigner et positionner un schéma d'une structure plus complexe pour inciter les slimes à construire selon leurs souhaits.

Ce jeu a été fait lors de l'Unijam 2019, une game jam organisée au sein de Télécom SudParis, l'école où j'ai étudié. Le thème était : "Ne craignez pas d'être lent, craignez seulement d'être à l'arrêt (proverbe chinois)".

Lors du développement du jeu, j'ai de mon côté beaucoup travaillé sur deux *design patterns* : le premier en date était un schéma d'*Object Pooling*. L'un des principes du jeu était de le lancer une seule fois sur le stand de test, et qu'ensuite les différentes personnes puissent jouer et construire à partir des ruines des parties des personnes précédentes. L'object pooling était donc tout indiqué, pour ne pas avoir à ré-instancier de nouvelles slimes à chaque "nouvelle partie". 
L'autre *design pattern* était un groupe d'*Observers*. Puisque le jeu reposait sur de nombreux groupes d'objets de même types (arbres générant des slimes, slimes construisant des structures, etc...) exécutant des tâches similaires, et ayant besoin de notifier des groupes d'objets de façon simultanées, le schéma d'*observer* permet de plus facilement garder la trace de qui doit être notifié.
Comme beaucoups d'autres jeux de game jam, ce jeu souffre d'un certain nombre de bugs, mais ma fierté reste d'avoir réussi à en faire une expérience jouable et agréable.

Notre équipe de 4, 2 développeurs venant de Télécom SudParis, et 2 élèves de la [license pro "Métiers du jeu vidéo" de Bobigny](https://iutb.univ-paris13.fr/formations/metiers-du-multimedia-et-de-linternet/licence-pro-metiers-du-jeu-video/), a remporté les prix du meilleur concept et du meilleur respect du thème.


Vous trouverez le dépôt github du projet [ici](https://github.com/matthias4217/grow-and-rest). 
