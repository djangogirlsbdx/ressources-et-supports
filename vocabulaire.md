# Vocabulaire

Les mots ont une signification bien précise ; malheureusement, en informatique, il nous arrive d'avoir un vocabulaire... peu commun.

Voici quelques définitions importantes pour vous aider à mieux comprendre la programmation en Python.


### Indentation

> Décalage d'une ligne de code depuis la bordure gauche.

Exemple :
```python
# la 2e ligne est indentée
if a == 2:
    print(a)
```


### Définition (ou Déclaration) _vs._ Appel de fonction

> La **définition** (**déclaration**) d'une fonction décrit le comportement d'une fonction suivant ces entrées, et ce qu'elle retourne.

> L'**appel** d'une fonction, c'est l'utilisation de la fonction sur des entrées spécifiques.

Exemple :
```python
# définition
def addition(a, b):
    return a + b

# appel de la fonction sur les entrées 1 et 2
addition(1, 2)
```


### Concaténation

> Concaténer deux chaines de caractères, c'est les mettre bout à bout pour créer une chaine unique.

Exemple :
```python
chaine1 = "Bonjour "
chaine2 = "les Girls !"

# afficher la concaténation des deux chaines
print(chaine1 + chaine2)
```
