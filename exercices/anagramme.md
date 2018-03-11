# Anagramme


## Première version

Écrire une fonction qui prend deux chaines de caractères en entrée, et retourne `True` si elles sont des anagrammes l'une de l'autre, `False` sinon.

```python
>anagramme('chien', 'niche')
True
>anagramme('pamplemousse', 'abricot')
False
```


## Version avancée

Les chaines de caractères peuvent contenir des espaces, des [diacritiques](https://fr.wikipedia.org/wiki/Diacritique), des majuscules, etc. dont on ne tiendra pas compte.

```python
>anagramme('Pascal Obispo', 'Pablo Picasso')
True
>anagramme('Le commandant Cousteau', 'Tout commença dans l\'eau')
True
```
