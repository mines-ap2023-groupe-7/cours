# TP sur argparse

## Setup le TP

A faire depuis votre repertoire de agar.io.

* Penser à se mettre sur la branche 'main'
* Effectuer un `git pull` pour récupérer la dernière version
* Créer une branche `argparse-<nom_github>`


## Rajouter argparse au projet agar.io

### option '--verbose' / '-v'

L'objectif est de pouvoir modifier l'option de lancement pour pouvoir lancer agar.io en mode 'bavard'.

* Lorsque je lance `python main.py -v` cela doit rajouter des `print` un peu partout dans le code pour permettre de voir ce qu'il se passe dans le jeu.

### option '--bot' / '-b'

Lorsque je rajoute l'option `-b`, je deviens spectateur d'un bot (pas d'action de la sourie pour controller mon blob). Celui-ci se déplace de manière autonome -> vous choisissez comment (aléatoire ou deterministe).

### option '--screen 200x400' / '-s 200x400'

Permet de modifier la résolution initiale de l'écran.

### autre proposition d'option pour des PR simple...

Je laisse votre imagination me faire des propositions

## Rajouter la possibilité de lire un fichier de configuration

Objectif :

```
python main.py -c config.agar
```

avec un fichier `config.agar` au format suivant:

```
screen:200x500
bot:True
```

