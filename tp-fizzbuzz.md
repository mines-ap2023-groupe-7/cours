# TP sur les itérables - FizzBuzz

## Configuration du TP

À faire depuis votre répertoire de cours :

* Effectuez un `git pull` pour récupérer la dernière version.
* Créez une branche `fizzbuzz-<nom_github>`.
* Créez un fichier `fizzbuzz.py`.


## Le FizzBuzz

Voir [Fizz buzz sur Wikipedia](https://en.wikipedia.org/wiki/Fizz_buzz).

Objectif : créer un itérable qui compte en remplaçant les multiples de 3 par 'fizz', les multiples de 5 par 'buzz'.

```bash
$ python fizzbuzz.py 20
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
> fizzbuzz
> 16
> 17
> fizz
> 19
> buzz
```

Le code
Version basique
Code à trous :

```python
def fizzbuzz():
    # ...
    return enum

# Ajouter une condition pour que cela s'arrête à 20
for i in fizzbuzz():
    print(i)
    # ...
```


### Avec lanceur / point d'entrée

Ajoutez le code nécessaire pour permettre de lancer le programme via `python fizzbuzz.py 20`.

### FizzBuzz personnalisable

Ajoutez un dictionnaire permettant de paramétrer la fonction `fizzbuzz`. Le dictionnaire doit être de la forme { 3: "fizz", 5: "buzz" } pour le FizzBuzz 'classique' et, plus généralement, un dictionnaire clé -> valeur, avec clé le nombre à utiliser comme modulo et valeur : le texte à faire apparaître.

Éléments à ajouter pour les plus rapides :
* Un docstring pour la méthode `fizzbuzz`.
* Une valeur par défaut.
* Adapter les arguments du script pour permettre de passer les options pour un FizzBuzz personnalisable.
