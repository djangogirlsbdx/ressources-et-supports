# Moyenne

Objectif : coder une fonction permettant de calculer la moyenne d'un ensemble de notes.

  * en entrée, cette fonction prend en paramètre une liste de notes
  * en sortie, cette fonction retourne la moyenne de ces notes

Pour calculer une moyenne, nous allons :

  * effectuer la somme de toutes les notes
  * puis diviser cette somme par le nombre de notes


#### Somme de toutes les notes

```python
somme = 0
for note in notes:
    somme += note
```


#### Diviser par le nombre de notes

```python
nombre_de_notes = len(notes)
somme / nombre_de_notes
```


## Solution

```python
def moyenne(notes):
    somme = 0
    for note in notes:
        somme += note

    nombre_de_notes = len(notes)
    return somme / nombre_de_notes
```

## Utilisation

```python
notes = [ 9, 12, 11, 8, 16, 14, 18 ]
resultat = moyenne(notes)
print(resultat)
```
