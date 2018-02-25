# Salutations

Objectif : afficher un message d'accueil à plusieurs personnes.

  * les personnes à saluer seront dans une liste


## Solution naïve

```python
personnes_presentes = [ "Rose", "Iris", "Lila", "Petunia", "Jasmine" ]
print("Bonjour " + personnes_presentes[0] + " !")
print("Bonjour " + personnes_presentes[1] + " !")
print("Bonjour " + personnes_presentes[2] + " !")
print("Bonjour " + personnes_presentes[3] + " !")
print("Bonjour " + personnes_presentes[4] + " !")
```

... Heureusement qu'il n'y a pas 200 personnes à saluer.

## Solution

```python
personnes_presentes = [ "Rose", "Iris", "Lila", "Petunia", "Jasmine",
                        "Marguerite", "Violette", "Hortense" ]

for prenom in personnes_presentes:
  print("Bonjour " + prenom + "!")
```
