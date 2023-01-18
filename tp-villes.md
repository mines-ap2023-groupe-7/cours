# TP sur les villes

## Objectif

Nous allons créé un script qui permet de générer un nouveau nom de ville qui sonne comme une ville francaise.

Pour cela, on va s'inspirer d'un process de Markov (cf: https://fr.wikipedia.org/wiki/Cha%C3%AEne_de_Markov).

L'idée est relativement simple : on cherche a estimer la probabler d'apparence des lettres a partir d'un référenciel (fourni) de ville
(voir fichier villes.csv). Grace a ces données on estimera la valeur `P(l1, l2)` qui est la probabilité de voir `l2` apres avoir vu `l1`.

## Setup le TP

A faire depuis un nouveau répertoire.

* Penser à faire à `git init` (il n'y a pas de raison de ne pas commiter de temps le projet)

## Lecture de fichier de ville

* Faire une fonction qui lit le fichier de ville et qui renvoie la liste des strings de nom de villes
* Avec `map`. Transformer cette liste en liste de liste de characters.

## Structure de donnée

Nous allons utiliser la structure suivante :

```
counter = { 'A': { 'B': 100, ... }, 'B': { 'E': 42, ... }}
# ici 100 représente le nombre de 'B' présent apres le 'A'

Ecrire une function qui prends la liste de mot en entre et renvoie le compteur. ! Penser a inclure les espaces et un charactere pour indiquer la 'fin du nom de ville'.

## On finit le générateur

* On écrit une function avec le counter et une lettre qui renvoie une lettre  (selon les probas pertinentes).

* On écrit notre générateur de nom de ville francaise.


## Pour aller plus loin

Pour améliorer le générateur, on peut regarder une succession de 3 lettres au lieu de 2. Comment peut-on modifier notre script pour intégrer cela ?


