# Article 221-II-1/07-1

Calcul du facteur "pi"

1 Le facteur pi pour un compartiment ou groupe de compartiments doit être calculé conformément aux paragraphes 1.1 et 1.2, compte tenu des indications ci-après :

j = numéro attribué aux zones touchées par l'avarie situées le plus à l'arrière, la zone N°1 étant celle qui est située à l'arrière ;

n = nombre de zones adjacentes touchées par l'avarie ;

k = numéro d'une cloison longitudinale donnée servant de barrière à la pénétration transversale dans une zone d'avarie comptée à partir du bordé vers l'axe longitudinal. La valeur de k au bordé est égale à 0 ;

x1 = distance entre l'extrémité arrière de Ls et l'extrémité arrière de la zone considérée ;

x2 = distance entre l'extrémité arrière de Ls et l'extrémité avant de la zone considérée ;

b = distance transversale moyenne, en mètres, mesurée depuis le bordé, perpendiculairement à l'axe longitudinal au niveau de la ligne de charge maximale de compartimentage, jusqu'à un plan vertical hypothétique qui s'étend entre les limites longitudinales utilisées pour le calcul du facteur pi et qui est soit tangent, soit commun en totalité ou en partie, à la portion la plus à l'extérieur de la cloison longitudinale considérée. Ce plan vertical doit être orienté de manière à ce que la distance transversale moyenne jusqu'au bordé extérieur ait une valeur maximale, sans toutefois dépasser le double de la distance la plus faible entre le plan et le bordé. Si la partie supérieure d'une cloison longitudinale est située au-dessous de la ligne de charge maximale de compartimentage, on suppose que le plan vertical utilisé pour le calcul de b s'étend vers le haut jusqu'à la ligne de charge maximale de compartimentage. b ne doit être supérieur à B/2.

Si l'avarie ne touche qu'une seule zone :

pi = p(x1j,x2j) [r(x1j,x2j,bk) - r(x1j,x2j,bk-1)]

Si l'avarie touche deux zones adjacentes :

pi = p(x1j,x2j+1) [r(x1j,x2j+1,bk) - r(x1j,x2j+1,bk-1)]

- p(x1j,x2j) [r(x1j,x2j,bk) - r(x1j,x2j,bk-1)]

- p(x1j+1,x2j+1) [r(x1j+1,x2j+1,bk) - r(x1j+1,x2j+1,bk-1)]

Si l'avarie touche trois zones adjacentes ou plus :

pi = p(x1j,x2j+n-1) [r(x1j,x2j+n-1,bk) - r(x1j,x2j+n-1,bk-1)]

- p(x1j,x2j+n-2) - [r(x1j,x2j+n-2,bk) - r(x1j,x2j+n-2,bk-1)]

- p(x1j+1,x2j+n-1) [r(x1j+1,x2j+n-1,bk) - r(x1j+1,x2j+n-1,bk-1)]

+ p(x1j+1,x2j+n-2) [r(x1j+1,x2j+n-2,bk) - r(x1j+1,x2j+n-2,bk-1)]

dans ces formules, r(x1, x2,b0) = 0

1.1 Le facteur p(x1, x2) doit être calculé à l'aide des formules suivantes :

Longueur maximale hors tout normalisée de l'avarie : Jmax = 10/33

Point d'articulation dans la distribution : Jkn = 5/33

Probabilité cumulative à Jkn : pk = 11/12

Longueur maximale absolue de l'avarie : lmax = 60 m

Longueur de la distribution normalisée : L* = 260 m

Distribution stochastique de la densité à J = 0 :

bo = 2 (pk/Jkn - 1 - pk/Jmax- Jkn)

Lorsque Ls ≤ L* :

Jm = min {Jmax, lmax/Ls}

Jk = Jm/2 + 1 - √1 + ((1-2pk) boJm + 1/4bo2Jm2)/bo

b 12 = b0

Lorsque Ls > L* :

Jm* = min {Jmax, lmax/L*}

Jk* = Jm*/2 + 1 - √1 + ((1-2pk) boJm* + 1/4bo2Jm*2)/bo

Jm = Jm*.L*/Ls

B12 = 2 (pk/jk - 1-pk/Jm-Jk

B11 = 4 1-pk/(Jm-Jk)Jk - 2 pk/Jk2

B21 = -2 1-pk/(Jm-Jk)2

B22 = -b21Jm

Longueur d'avarie adimensionnelle :

J = (x2 - x1)/Ls

Longueur normalisée d'un compartiment ou groupe de compartiments :

Jn est pris comme égal à J ou à Jm si cette dernière valeur est inférieure.

1.1.1 Si aucune des limites du compartiment ou groupe de compartiments considéré ne coïncide avec l'extrémité arrière ou l'extrémité avant :

J ≤ Jk :

p(x1x2,) = p1 1/6 J2 (b11J+3b12)

J > Jk :

p(x1x2) = p2 = - 1/3 b11Jk3 + ½ (b11J-b12) Jk2 + b12JJk - 1/3 b21 (Jn3-Jk3)

+ 1/2 (b21J-b22) (Jn2-Jk2) + b22J (Jn-Jk)

1.1.2 Si la limite arrière du compartiment ou groupe de compartiments considéré coïncide avec l'extrémité arrière ou si la limite avant du compartiment ou groupe de compartiments considéré coïncide avec l'extrémité avant :

J ≤ Jk :

p (x1, x2) = 1/2 (p1+J)

J > Jk :

p (x1, x2) = 1/2 (p2+J)

1.1.3 Lorsque le compartiment ou groupe de compartiments considéré s'étend sur toute la longueur de compartimentage (Ls) :

p (x1, x2) = 1

1.2 On obtient le facteur de réduction r(x1, x2, b) à l'aide de la formule suivante :

r (x1, x2, b) = 1 - (1-C).[1-G/p (x1,x2)]

dans laquelle :

C = 12.Jb.(-45.Jb + 4), où

Jb = b/15.B

1.2.1 Si le compartiment ou groupe de compartiments considéré s'étend sur toute la longueur de compartimentage (Ls) :

G = G1 = 1/2 b11 Jb2 + b12 Jb

1.2.2 Si aucune des limites du compartiment ou groupe de compartiments considéré ne coïncide avec l'extrémité arrière ou l'extrémité avant :

G = G2 = - 1/3 b11 J03 + 1/2 (b11J-b12)J02 + b12 JJ0 , où

J0 = min (J, Jb)

1.2.3 Si la limite arrière du compartiment ou groupe de compartiments considéré coïncide avec l'extrémité arrière ou si la limite avant du compartiment ou groupe de compartiments considéré coïncide avec l'extrémité avant :

G = ½.(G2+G1.J)
