# Article Annexe 1

AUTOCONTRÔLE PAR MODULO 11

Ce modulo dépiste pratiquement toutes les erreurs de transcription et les inversions de chiffres simples et doubles. Il dépiste aussi 90 % des autre erreurs.

Le chiffre d'autocontrôle est le résultat des opérations arithmétiques suivantes :

1. Multiplication par les chiffres 2, 3, 4, 5, 6 et 7 respectivement des chiffres du nombre dont l'exactitude doit être vérifiée en commençant par celui des unités. Si le nombre comporte plus de 6 chiffres, recommencer au 7e la première séquence des multiplications.

2. Addition des produits de ces multiplications.

3. Division du total par 11.

4. a) Lorsque ce total est exactement divisible par 11, le chiffre d'autocontrôle est 0.

b) Dans le cas contraire, déduire le reste de la division du nombre 11 : la différence est le chiffre d'autocontrôle.

Exemple : soit à déterminer le chiffre d'autocontrôle du nombre 453 267.

Multiplications à effectuer :

(7 × 2) ; (6 × 3) ; (2 × 4) ; (3 × 5) ; (5 × 6) ; (4 × 7)

Produits obtenus :

14 ; 18 ; 8 ; 15 ; 30 ; 28.

Total de ces produits = 113.

Reste de la division de 113 par 11 = 3.

Déduire 3 de → 11 la différence = 8 est le chiffre d'autocontrôle.

Le nombre devient : 4 532 678 ou 8 453 267.

NB : Lorsque la division donne 1 comme reste, le nombre ne peut être contrôlé par modulo 11 au moyen d'un seul chiffre car, dans ce cas, la différence entre le nombre 11 et le reste 1 est 10, nombre à 2 chiffres. Par convention, la clé sera alors également le chiffre 1.
