# TP sur les iterables - Fizzbuzz

## Setup le TP

A faire depuis votre repertoire du cours

* Effectuer un `git pull` pour récupérer la dernière version
* Créer une branche `fizzbuzz-<nom_github>`
* Créer un fichier fizzbuzz.py


## Le fizzbuzz

Voir https://en.wikipedia.org/wiki/Fizz_buzz.

Objectif créer un enumerable qui compte en remplacant les multiples de 3 par 'fizz', les multiples de 5 par 'buzz'.

```bash
$ python fizzbuzz 20
> 1
> 2
> fizz
> 4
> buzz
> fizz
> 7
> 8
> fizz
> buzz
> 11
> fizz
> 13
> 14
> fizz buzz
> 16
> 17
> fizz
> 19
> buzz
```

## Le code

### Version basic
Code à trou

```python
def fizzbuzz():
    # ...
    return enum

# rajouter une condition pour que cela s'arrète à 20
for i in fizzbuz():
    print(i)
    #...




### Avec lanceur / point d'entrée

Rajouter le code nécessaire pour pouvoir permettre de lancer le programme via `python fizzbuzz.py 20`

### Fizzbuzz customizable

Rajouter un dictionnaire permettant de paramètrer la function `fizzbuzz`. Le dictionnaire doit être de la forme { 3: "fizz", 5: "buzz" } pour le fizzbuzz 'classique' et plus généralement un dictionnaire clef -> valeur avec clef le nombre à utiliser comme modulo et valeur: le texte a faire apparaitre.

Les éléments à rajouter pour les plus rapide :
* un doctring pour la méthode 'fizzbuzz'
* Une valeur par défault
* adapter les arguments du script pour permettre de passer les options pour un fizzbuzz customizable.
