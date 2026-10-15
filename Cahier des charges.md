# Mini-Projet Jeu Vidéo 2D - Cahier des charges

## Introduction

Ceci est le cahier des charges retraçant le contenu de notre mini-projet consistant à créer un jeu vidéo en deux dimensions à l'aide du module de code ```pygame```. Il contient la liste des fonctionnalités de notre jeu, ainsi que des précisions et descriptions complètes de chaque aspect de celui-ci dans les moindres détails. Bonne lecture !

## Présentation

Pour ce projet, nous avons décidé de recréer le jeu d'arcade **Tron** , en rajoutant des items pour rendre les parties plus longues et dynamiques !

Le principe de **Tron** est simple : deux joueurs contrôlent chacun un joueur, ici une moto (ou **lightcycle**) en l'occurence, qui avance continuellement. Les joueurs créent une traînée derrière eux qui fait office d'obstacle mortel. Le but du jeu est de diriger sa **lightcycle** afin d'éviter d'entrer en collision avec les limites du terrain de jeu, la **grille** , et avec les traînées. Le survivant gagne la partie !

## Modes de jeu et fenêtres

Le jeu comporte 7 "fenêtres" :

- **La fenêtre d'accueil**, c'est la fenêtre de base quand on lance le jeu. Elle permet d'aller jouer une partie, consulter la liste des succès et d'aller au menu des I-Memes* via différents boutons.
- **La grille**, c'est la fenêtre qui nous permettra de jouer une partie. Elle affiche le terrain de jeu, les données statistiques telles que le temps, le score, le nombre de collectibles récupérés et le nombre de frôlements effectués.
- **La liste des succès**. Elle permet de consulter l'ensemble des succès du jeu, les complétés et les non-complétés.
- **Le menu des I-Memes***. Il permet de voir les I-Memes* débloqués et de sélectionner celui que l'on veut utiliser lors de nos prochaines parties. Il sont aussi classés par rareté et catégories de succès.
- **Le menu de défaite** du **Joueur 1**.
- **Le menu de défaite** du **Joueur 2**.
- **Le menu d'égalité**, fin de partie un peu rare.

**N.B. : Le terme "I-Meme" vient de la contraction entre "item" et "meme", ingénieux non ?* 

## Joueurs

Le jeu comporte 2 joueurs, un commençant sur le côté gauche de la **grille**, l'autre commençant sur le côté droit de la **grille**.

## Mouvements

Les joueurs avancent *continuellement*. Le **Joueur 1** peut changer sa direction avec les touches z, q, s, d, pour aller respectivement en haut, à gauche, en bas, à droite. Le **Joueur 2** peut changer sa direction avec les flèches directionnelles du clavier.

## Statistiques

Chaque joueur comporte plusieurs statistiques décrites ci-dessous. Ces statistiques ne correspondent pas à une valeur globale mais sur une partie.

Les statistiques suivantes sont :

- le temps
- le score
- les frôlements, un événement qui apparaît lorsqu'on esquive une traînée ou un mur de justesse
- les collectibles, des objets qui apparaîssent de temps en temps sur la grille et que le joueur peut récolter en passant dessus.


## Succès

Chaque joueur peut accomplir des succès rangés dans plusieurs catégories :

- le temps
- le score
- les frôlements
- les collectibles

Certains succès sont cachés ! Cherchez-bien !

## I-Memes

Chaque succès a comme récompense un I-Meme que l'on peut équiper et utiliser dans la grille. Chaque I-Meme possède un temps de rechargement de sa capacité plus ou moins long selon sa rareté.

Il existe plusieurs raretés :

- rareté rare
- rareté épique
- rareté légendaire

Certains I-Memes sont cachés ! Cherchez-bien !


###### Liam CHAPLIN, Léopold SIMEANT
