# TP 'ca sent le sapin'

## Configuration du TP

À faire depuis votre répertoire de cours :

* Effectuez un `git pull` pour récupérer la dernière version.
* Effectuez un `git stash` pour mettre de coté ce qui n'est pas commité
* Créez une branche `sapin-<nom_github>`.
* Créez un fichier `sapin.py`.
* On créé un environnement conda dédié : `conda create -n sapin python=3.11` puis `conda activate sapin`


## Le sujet

Sujet relativement simple en 2 parties. 

L'objectif est de faire une petite application avec un sapin sur lequel on fait apparaitre des figures/boules colorés.

## Projet minimal

1. On installe le module 'pygame'
2. Version minimal pour une application :
 
```python
import pygame

pygame.init()

screen = pygame.display.set_mode( (640, 480) )

clock = pygame.time.Clock()

while True:
    clock.tick(1)

    for event in pygame.event.get():
        pass

    screen.fill( (0, 255, 0) )

    pygame.display.update()
```

3. On vérifie qu'on arrive à lancer le jeu + le tuer (on kill le process)

### Le TP

#### Background

1. On change l'orientation du jeu
2. Trouver/générer une belle image de fond avec un sapin sans décorations.
3. On charge cette image dans le jeu.
 
#### Les boules

Objectifs, lorsqu'on clique, on affiche une boule

![CleanShot 2023-12-19 at 10.13.00.gif](..%2F..%2FLibrary%2FApplication%20Support%2FCleanShot%2Fmedia%2Fmedia_ZItDfxmKLr%2FCleanShot%202023-12-19%20at%2010.13.00.gif)

### Les évolutions

1. Lorsqu'on reclique sur l'image on en change la couleur
2. Tracer une autre figure
3. Faire varier la couleur des boules dans le temps