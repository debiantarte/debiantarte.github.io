---
layout: post
title: "Grow & Rest"
lang: en
ref: grow-and-rest
thumbnail: grow_rest_cover.png
thumbnail-alt: Grow & Rest
description: A contemplative god-game made in C# with Unity for the Unijam 2019 game jam.
tags: perso gamejam game csharp
---

# About [Grow & Rest](https://resteam.itch.io/rest-grow)

Grow & Rest is a contemplative god-game about slimes building structures over time. Once a slime reaches it's destination, it solidifies, becoming a new brick in a greater structure.

The player can choose to just wait and see the little slimes build simple structures, or select a scheme for a more complex one and left click and hold somewhere to make the slimes build the structure there.

The game was made during the Unijam 2019, a game jam hosted by Télécom SudParis for its students. The theme was "Don't be afraid to be slow, be afraid to stop. (chinese proverb)". 

During the development of the game, I worked especially on 2 design patterns, the first of which was *Object Pooling*. Since the gameplay was meant to revolve around players coming and going to our stand, building upon the ruins of eachother's playthroughs, it was necessary to pool slimes and other objects, to save time and not just intantiate new objects every new playthrough.
The other pattern used was *Observers*. Since the game is built upon several groups of objects of the same types, doing similar tasks, and having to notify other objects or groups of objects, having a way to easily track who gets to be notified by what was primordial. 
Like many other jam games, the game suffers from some bugs, but all in all, I am proud to have been able to create a playable and enjoyable experience with this game. 

Our team of 4 won the price for the best concept and respect of the theme. 



See the github repository for the project [here](https://github.com/matthias4217/grow-and-rest).
