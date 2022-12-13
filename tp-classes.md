# TP sur les classes

## Setup le TP

A faire depuis votre repertoire de travail

```bash
(base) git clone git@github.com:flotpython/exos.git

(base) cd exos

(base) conda create -n students python=3.10

(base) conda activate students
# votre terminal doit indiquer le nom d'environnement:
(students) $


# en suite
(students) $ jupyter notebook .
```

On peut alors ouvrir le jupyter notebook du td et aller dans python-tps/students-grades/README-students.md

## Réaliser le TP

2 options s'offre à vous :

### (option simple) Dans le notebook

Compléter dans le notebook les class Student et Class et réexuter a chaque fois les cellules pertinentes

### (option python) Dans un nouveau projet

* Ouvrir un nouveau projet
* (optionnel) tracker le projet avec git `git init`
* Ecrire le code `Student` dans un module student.py
* Copier dans `main.py` les boucles `try / catch` du notebook
* Rajouter au `main.py` l'import qui va bien
* Lancer `python main.py` pour tester notre code
