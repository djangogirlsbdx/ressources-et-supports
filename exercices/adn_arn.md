# ADN - ARN

Étant donné une séquence d'ADN, retourner son complémentaire ARN.

Les nucléotides qui forment une séquence d'ADN sont : Adénine (A), Cytosine (C), Guanine (G) et Thymine (T).

Les nucléotides qui forment une séquence d'ARN sont : Adénine (A), Cytosine (C), Guanine (G) et Uracile (U).

Étant donné une séquence ADN, la séquence ARN correspondante est formée en remplaçant chaque nucléotide par son complément :
  * G -> C
  * C -> G
  * T -> A
  * A -> U

```python
> adn_to_arn('C')
G
> adn_to_arn('G')
C
> adn_to_arn('T')
A
> adn_to_arn('A')
U
> adn_to_arn('ACGTGGTCTTAA')
UGCACCAGAAUU
```
