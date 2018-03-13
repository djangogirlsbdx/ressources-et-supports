## Variables

```python
# un entier
a = 42

# une chaine de caractères
b = "Bonjour !"

# une liste
c = [ 1, 2, 3 ]
```


## Fonctions

```python
# déclaration
def addition(a, b):
  return a + b

# appel "direct"
addition(1, 3)

# ou appel utilisant des variables
premier_nombre = 1
deuxieme_nombre = 2
addition(premier_nombre, deuxieme_nombre)
```


## Boucles

```python
# for (pour)
for i in range(10):
  print(i)

# while (tant que)
i = 0
while i < 10:
  print(i)
  i += 1
```


## Listes

```python
fruits = [ "pomme", "abricot", "poire", "banane" ]

for fruit in fruits:
  print(fruit)

# accès à un élément par son index
fruit = fruits[0]
```


## Dictionnaires

```python
annuaire = { 'Rose': 0611, 'Iris': 0612, 'Lila': 0613 }
numero = annuaire['rose']
```
