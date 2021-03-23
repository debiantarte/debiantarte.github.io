---
title: Feudal Overlords
layout: post
description: Mon premier jeu jouable, fait pour un cours de programmation en C++
lang: fr
ref: feudal-overlords
thumbnail: feudal_overlords_cover.png
thumbnail-alt: Feudal Overlords
thumbnail-size: "65%"
thumbnail-margin: "auto"
tags: school game cpp
---
# À propos de [Feudal Overlords](https://github.com/debiantarte/feudal-overlords)

Feudal Overlords est le premier projet que j'ai considéré comme méritant l'appellation de "jeu" (j'avais participé à quelques game jams auparavant, mais les résultats étaient à peine testables). Le projet, développé en C++, faisait forme d'évaluation pour un cours de programmation en C++. Nous avions pour consignes de travailler en binôme, en utilisant la bibliothèque graphique SFML ainsi que deux autres bibliothèques externes de notre choix. L'accent était mis sur le besoin d'avoir une hiérarchie bien structurée et d'éviter l'emploi de "[singletons](https://gameprogrammingpatterns.com/singleton.html)".

Le game design était penser pour faire un jeu de stratégie au tour par tour, avec une notion de contrôle de territoires : chaque territoire sur la carte produit une quantité de troupes par tour, et chaque joueur-euse démarrait avec un territoire symbolisant sa capitale, l'objectif étant de capturer la capitale adverse.

Ce projet a connu de nombreux problèmes au cours de son développement. Avec mon binôme, nous avions fait l'erreur de commencer par coder des aspects du gameplay très peu visuels, ce qui a rendu l'implémentation graphique ensuite plus fastidieuse. 

Le projet n'avait pas reçu une note satisfaisante lors de la première évaluation, alors nous avons largement retravaillé le gameplay, notamment les retours/feedbacks visuels et textuels.
Lors du rattrapage, le projet a reçu de bien meilleurs retours, et ces erreurs m'ont permis de faire un peu plus attention aux feedbacks dans mes projets suivants.
