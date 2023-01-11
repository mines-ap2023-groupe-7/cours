# TP sur argparse

## Setup le TP

A faire depuis votre repertoire depuis un nouveau répertoire.

* Penser à faire à `git init` (il n'y a pas de raison de ne pas commiter de temps le projet

## L'application de syracuse

On appelle `application de syracuse` une function qui pour un entier `n` :
* s'il est pair renvoie sa moitié
* sinon renvoie `3n + 1`

Missions simples :
1. Ecrire une méthode qui effectue l'application de syracuse
2. En écrire la documentation docstring
3. En faire un script (pour le lancer en commande)
4. Faire de '3' un paramètre nommé `mult` avec 3 comme valeur par défault
5. Ecrire `syr_lambda` comme une lambda qui prend un paramêtre et renvoie la prochaine itération
6. Comment se comporte cette fonction lorsqu'on itère plusieurs fois sur elle-même ? Comment peut-on montrer cela ? 

## Le 'vol'

On appelle vol le nombre d'itération nécessaire pour un nombre avant de retourner sur '1'.

1. Implémenter une méthode pour connaitre le vol d'un nombre
2. Comment peut-on rendre cette méthode le plus fonctionnel possible ? Pour rappel, 'fonctionnel' = pas d'etat/variables garder en mémoire.
3. Modifier cette function pour lui pouvoir lui passer une fonction/lambda
4. Comment peut-on utiliser cette approche pour pouvoir simplement passer des application de syracuse avec d'autre nombre que '3'
