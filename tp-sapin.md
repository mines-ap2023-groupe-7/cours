# TP 'Ça sent le sapin'

## Configuration du TP

**Objectif :** Préparer votre environnement de travail pour le TP.

**Instructions :**
1. **Récupérez la dernière version des cours :**
   - Exécutez `git pull` dans votre répertoire de cours.
2. **Sauvegardez votre travail en cours :**
   - Utilisez `git stash` pour mettre de côté les modifications non commitées.
3. **Préparez votre espace de travail pour le TP :**
   - Créez une nouvelle branche nommée `sapin-<nom_github>`.
   - Créez un fichier `sapin.py` dans cette branche.
4. **Configurez l'environnement Python :**
   - Créez un environnement conda dédié : `conda create -n sapin python=3.11`.
   - Activez l'environnement : `conda activate sapin`.

## Le Sujet

**But :** Réaliser une application graphique avec Pygame affichant un sapin de Noël et permettant d'y ajouter des décorations interactives.

### Projet Minimal

**Objectif :** Mettre en place l'application de base avec Pygame.

**Étapes :**
1. Installez le module Pygame : `pip install pygame`.
2. Implémentez une application Pygame basique :
   ```python
   import pygame

   pygame.init()

   screen = pygame.display.set_mode((640, 480))
   clock = pygame.time.Clock()

   while True:
       clock.tick(1)

       for event in pygame.event.get():
           pass

       screen.fill((0, 255, 0))
       pygame.display.update()
   ```
3. Testez l'application :
   - Lancez l'application.
   - Assurez-vous que vous pouvez fermer l'application correctement.

### Le TP en Détail

#### Background

**Objectif :** Personnaliser l'arrière-plan de l'application.

**Étapes :**
1. Modifiez l'orientation de l'affichage.
2. Trouvez ou créez une image de fond représentant un sapin sans décorations.
3. Intégrez cette image comme arrière-plan dans l'application.

#### Les Boules

**Objectif :** Ajouter des interactions pour décorer le sapin.

![animation-sapin.gif](animation-sapin.gif)

**Étapes :**
1. Implémentez une fonctionnalité permettant d'afficher à l'écran une liste de boules de noel (bien choisir sa structure de données pour les boules).
2. Ajoutez la possibilité de rajouter une boule à chaque click de souris.

### Évolutions

**Objectif :** Améliorer et diversifier les interactions.

**Étapes :**
1. Permettez de changer la couleur de la boule en recliquant dessus.
2. Gérer plusieurs taille de boules si on click sur le bouton droit ou le bouton gauche.
3. Ajoutez la possibilité de tracer d'autres formes sur le sapin.
4. Implémentez un effet où la couleur des boules varie avec le temps.