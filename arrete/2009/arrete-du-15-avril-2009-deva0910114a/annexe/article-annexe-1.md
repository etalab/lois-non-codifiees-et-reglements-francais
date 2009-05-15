# Article Annexe 1

**CODAGE DES BALISES DE DÉTRESSE AÉRONAUTIQUES**

1. Protocole de localisation

Dans le protocole de localisation normalisé (standard location protocol), toutes les données d'identification et de localisation sont codées en binaire, le bit de plus faible poids étant à droite.

Dans le protocole de localisation normalisé, l'identification de la balise ou de l'aéronef est codée de façon standard sur 24 bits dans la première partie du message (PDF1). Une information de position avec une résolution de 15 minutes se trouve également dans cette première partie. Une résolution plus fine (4 secondes) de la position est également codée dans la deuxième partie du message (PDF2).

Pour l'information d'identification, seuls sont autorisés le code 24 bits de l'adresse de l'aéronef ou le numéro de série de la balise (ELT ou PLB).

Lorsqu'un aéronef est doté de plusieurs balises de détresse, une seule doit comporter l'adresse 24 bits. Toutes les autres doivent être codées avec le numéro de série de la balise.

1.1. Codage du premier champ de données protégé (PDF1)

1.1.1. Avec l'adresse 24 bits de l'aéronef

<div align="center">

<table>
<tbody>
<tr>
<th>BITS<br/>
</th>
<th>25<br/>
</th>
<th>26<br/>
</th>
<th>27 À 36<br/>
</th>
<th>37 À 40<br/>
</th>
<th>41 À 64<br/>
</th>
<th>65<br/>
</th>
<th>66 À 74<br/>
</th>
<th>75<br/>
</th>
<th>76 À 85<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">Code pays<br/>
</td>
<td align="center">0011<br/>
</td>
<td align="center">Adresse 24 bits<br/>de l'aéronef<br/>
</td>
<td align="center">Pos lat.<br/>
</td>
<td align="center">Lat.<br/>
</td>
<td align="center">Pos long.<br/>
</td>
<td align="center">Long <br/>
</td>
</tr>
<tr>
<td colspan="10">Bit 25 : 1 pour message long.<br/>Bit 26 : 0 pour protocole de localisation.<br/>Bits 27 à 36 : 227 pour la France métropolitaine ; 226 pour les appareils de la défense ; 329 pour la Guadeloupe ; 347 pour la Martinique ; 540 pour la Nouvelle-Calédonie ; 546 pour la Polynésie française ; 578 pour Wallis et Futuna ; 660 pour La Réunion et Mayotte ; 745 pour la Guyane française.<br/>Bits 37 à 40 : 0011 indique qu'il s'agit d'une adresse 24 bits.<br/>Bits 41 à 64 : adresse 24 bits de l'aéronef.<br/>Bit 65 : 0 indique qu'il s'agit d'une latitude Nord ; 1 indique qu'il s'agit d'une latitude Sud.<br/>Bits 66 à 74 : valeur en degrés de la latitude (de 0 à 90 par incrémentation de 1/4 de degré).<br/>Bit 75 : 0 indique qu'il s'agit d'une longitude Est ; 1 indique qu'il s'agit d'une longitude Ouest.<br/>Bits 76 à 85 : valeur en degrés de la longitude (de 0 à 180 par incrémentation de 1/4 de degré).<br/>
</td>
</tr>
</tbody>
</table>

</div>

1.1.2. Avec le numéro de série de la balise

<div align="center">

<table>
<tbody>
<tr>
<th>Bits<br/>
</th>
<th>25<br/>
</th>
<th>26<br/>
</th>
<th>27 À 36<br/>
</th>
<th>37 À 40<br/>
</th>
<th>41 À 50<br/>
</th>
<th>51 À 64<br/>
</th>
<th>65<br/>
</th>
<th>66 À 74<br/>
</th>
<th>75<br/>
</th>
<th>76 À 85<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">Code pays<br/>
</td>
<td align="center">XXXX<br/>
</td>
<td align="center">TAC<br/>
</td>
<td align="center">Numéro de série<br/>
</td>
<td align="center">Pos<br/>lat.<br/>
</td>
<td align="center">Lat.<br/>
</td>
<td align="center">Pos long.<br/>
</td>
<td align="center">Long <br/>
</td>
</tr>
<tr>
<td colspan="11">Bit 25 : 1 pour message long.<br/>Bit 26 : 0 pour protocole de localisation.<br/>Bits 27 à 36 : 227 pour la France métropolitaine ; 226 pour les appareils de la défense ; 329 pour la Guadeloupe ; 347 pour la Martinique ; 540 pour la Nouvelle-Calédonie ; 546 pour la Polynésie française ; 578 pour Wallis et Futuna ; 660 pour La Réunion et Mayotte ; 745 pour la Guyane française.<br/>Bits 37 à 40 : 0100 indique qu'il s'agit d'un ELT ; 0111 indique qu'il s'agit d'une PLB.<br/>Bits 41 à 50 : numéro du certificat d'approbation de type COSPAS/SARSAT de la balise de détresse.<br/>Bits 51 à 64 : numéro de série de la balise de détresse.<br/>Bit 65 : 0 indique qu'il s'agit d'une latitude Nord ; 1 indique qu'il s'agit d'une latitude Sud.<br/>Bits 66 à 74 : valeur en degrés de la latitude (de 0 à 90 par incrémentation de 1/4 de degré).<br/>Bit 75 : 0 indique qu'il s'agit d'une longitude Est ; 1 indique qu'il s'agit d'une longitude Ouest.<br/>Bits 76 à 85 : valeur en degrés de la longitude (de 0 à 180 par incrémentation de 1/4 de degré).<br/>
</td>
</tr>
</tbody>
</table>

</div>

1.2. Codage du second champ de données protégé (PDF2)

Le codage de ce second champ de données protégé est identique pour tous les protocoles de localisation normalisés.

<div align="center">

<table>
<tbody>
<tr>
<th>Bits<br/>
</th>
<th>107 À 110<br/>
</th>
<th>111<br/>
</th>
<th>112<br/>
</th>
<th>113<br/>
</th>
<th>114 À 118<br/>
</th>
<th>119 À 122<br/>
</th>
<th>123<br/>
</th>
<th>124 À 128<br/>
</th>
<th>129 À 132<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">1101<br/>
</td>
<td align="center">0 ou 1<br/>
</td>
<td align="center">0 ou 1<br/>
</td>
<td align="center">Signe<br/>
</td>
<td align="center">Minutes<br/>
</td>
<td align="center">Secondes<br/>
</td>
<td align="center">Signe<br/>
</td>
<td align="center">Minutes<br/>
</td>
<td align="center">Secondes <br/>
</td>
</tr>
<tr>
<td colspan="10">Bit 107 à 110 : 1101 valeur fixe.<br/>Bit 111 : 0 signifie que la position codée dans PDF-1 est issue d'un dispositif de navigation externe ; 1 signifie que la position codée dans PDF-1 est issue d'un dispositif de navigation interne.<br/>Bit 112 : 0 signifie qu'il n'y a pas de transmetteur 121,5 MHz dans la balise ; 1 signifie qu'il y a un transmetteur 121,5 MHz dans la balise.<br/>Bits 113 à 122 : présentent la correction à apporter à la latitude codée dans PDF-1, avec une précision de 4 secondes.<br/>Bit 113 : 0 correspond au signe ― (moins) ; 1 correspond au signe + (plus).<br/>Bits 114 à 118 : minutes (de 0 à 30 par incrémentation de 1 minute).<br/>Bits 119 à 122 : secondes (de 0 à 56 par incrémentation de 4 secondes).<br/>Bits 123 à 132 : présentent la correction à apporter à la longitude codée dans PDF-1, avec une précision de 4 secondes.<br/>Bit 123 : 0 correspond au signe ― (moins) ; 1 correspond au signe + (plus).<br/>Bits 124 à 128 : minutes (de 0 à 30 par incrémentation de 1 minute).<br/>Bits 129 à 132 : secondes (de 0 à 56 par incrémentation de 4 secondes).<br/>
</td>
</tr>
</tbody>
</table>

</div>

2. Protocole d'usager

Les protocoles d'usager, autorisés dans les conditions décrites à l'article 7, sont les protocoles utilisant l'adresse 24 bits de l'aéronef ou le numéro de série de la balise.

Dans le cas des ELT sans données de navigation, on utilise le format de message court. Dans le cas des ELT avec des données de navigation, on utilise le format de message long.

2.1. Format de message court

2.1.1. Avec l'adresse 24 bits de l'aéronef

<div align="center">

<table>
<tbody>
<tr>
<th>Bits<br/>
</th>
<th>25<br/>
</th>
<th>26<br/>
</th>
<th>27 À 36<br/>
</th>
<th>37 À 39<br/>
</th>
<th>40 À 42<br/>
</th>
<th>43<br/>
</th>
<th>44 À 67<br/>
</th>
<th>68 À 73<br/>
</th>
<th>74 À 83<br/>
</th>
<th>84 ET 85<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">Code pays<br/>
</td>
<td align="center">011<br/>
</td>
<td align="center">011<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">Adresse 24 bits<br/>de l'aéronef<br/>
</td>
<td align="center">Numéro<br/>de l'ELT<br/>
</td>
<td align="center">TAC<br/>
</td>
<td align="center">01 <br/>
</td>
</tr>
<tr>
<td colspan="11">Bit 25 : 0 pour message court.<br/>Bit 26 : 1.<br/>Bits 27 à 36 : 227 pour la France métropolitaine ; 226 pour les appareils de la défense ; 329 pour la Guadeloupe ; 347 pour la Martinique ; 540 pour la Nouvelle-Calédonie ; 546 pour la Polynésie française ; 578 pour Wallis et Futuna ; 660 pour La Réunion et Mayotte ; 745 pour la Guyane française.<br/>Bits 37 à 39 : 011 indique qu'il s'agit d'un protocole de série.<br/>Bits 40 à 42 : 011 indique qu'il s'agit d'un ELT codé avec l'adresse 24 bits de l'aéronef.<br/>Bit 43 : 1 indique que le certificat d'approbation de type de COSPAS/SARSAT est encodé dans les bits 74 à 83.<br/>Bits 44 à 67 : adresse 24 bits de l'aéronef.<br/>Bits 68 à 73 : numéro de l'ELT lorsque plusieurs ELT sont à bord ;  0  s'il n'y en a qu'un.<br/>Bit 74 à 83 : numéro du certificat d'approbation de type délivré par COSPAS/SARSAT pour ce type de balise.<br/>Bits 84 à 85 : 01 indique la présence d'un moyen de radiolocalisation émettant sur 121,5 MHz.<br/>
</td>
</tr>
</tbody>
</table>

</div>

Nota. ― Le numéro de l'ELT lorsque plusieurs ELT sont à bord (bits 68 à 73) ainsi que le numéro de certificat d'approbation de type COSPAS/SARSAT (bits 74 à 83) sont encodés en binaire, le bit de plus faible poids étant à droite.

2.1.2. Avec le numéro de série de la balise

<div align="center">

<table>
<tbody>
<tr>
<th>Bits<br/>
</th>
<th>25<br/>
</th>
<th>26<br/>
</th>
<th>27 À 36<br/>
</th>
<th>37 À 39<br/>
</th>
<th>40 À 42<br/>
</th>
<th>43<br/>
</th>
<th>44 À 63<br/>
</th>
<th>64 À 73<br/>
</th>
<th>74 À 83<br/>
</th>
<th>84 ET 85<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">Code pays<br/>
</td>
<td align="center">011<br/>
</td>
<td align="center">000<br/>
</td>
<td align="center">1<br/>
</td>
<td align="center">N° de série<br/>
</td>
<td align="center">0000000000<br/>
</td>
<td align="center">TAC<br/>
</td>
<td align="center">01 <br/>
</td>
</tr>
<tr>
<td colspan="11">Bit 25 : 0 pour message court.<br/>Bit 26 : 1.<br/>Bits 27 à 36 : 227 pour la France métropolitaine ; 226 pour les appareils de la défense ; 329 pour la Guadeloupe ; 347 pour la Martinique ; 540 pour la Nouvelle-Calédonie ; 546 pour la Polynésie française ; 578 pour Wallis et Futuna ; 660 pour La Réunion et Mayotte ; 745 pour la Guyane française.<br/>Bits 37 à 39 : 011 indique qu'il s'agit d'un protocole de série.<br/>Bits 40 à 42 : 000 indique qu'il s'agit d'un ELT codé avec le numéro de série de la balise.<br/>Bit 43 : 1 indique que le certificat d'approbation de type de COSPAS/SARSAT est encodé dans les bits 74 à 83.<br/>Bits 44 à 63 : numéro de série de l'ELT.<br/>Bit 64 à 73 : 10 bits, tous à  0 .<br/>Bits 74 à 83 : numéro de certificat d'approbation de type COSPAS/SARSAT.<br/>Bits 84 à 85 : 01 indique la présence d'un appareil de radiolocalisation auxiliaire fonctionnant sur la fréquence 121,5 MHz.<br/>
</td>
</tr>
</tbody>
</table>

</div>

Nota. ― Le numéro de série de la balise (bits 44 à 63) ainsi que le numéro de certificat d'approbation de type COSPAS/SARSAT (bits 74 à 83) sont encodés en binaire, le bit de plus faible poids étant à droite.

2.2. Format de message long

Lorsqu'il s'agit d'un protocole de localisation d'usager (user location protocol), la précision issue des indications fournies par un dispositif de navigation est moins précise que dans le cas d'un protocole de localisation normalisé (standard location protocol).

Dans ce cas, le champ de données protégé (PDF1) est le même que dans le cas d'un message court (paragraphe 2.1), à l'exception du bit 25 qui prend la valeur 1.

Champ de données protégé (PDF2)

<div align="center">

<table>
<tbody>
<tr>
<th>Bits<br/>
</th>
<th>107<br/>
</th>
<th>108<br/>
</th>
<th>109 À 115<br/>
</th>
<th>116 À 119<br/>
</th>
<th>120<br/>
</th>
<th>121 À 128<br/>
</th>
<th>129 À 132<br/>
</th>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">Source<br/>
</td>
<td align="center">N/S<br/>
</td>
<td align="center">Degrés<br/>
</td>
<td align="center">Minutes<br/>
</td>
<td align="center">E/W<br/>
</td>
<td align="center">Degrés<br/>
</td>
<td align="center">Minutes <br/>
</td>
</tr>
<tr>
<td colspan="8">Bit 107 : 0 indique que la position est issue d'un dispositif de navigation externe ; 1 indique que la position est issue d'un dispositif de Navigation interne.<br/>Bit 108 : 0 indique qu'il s'agit d'une latitude Nord ; 1 indique qu'il s'agit d'une latitude Sud.<br/>Bit 109 à 115 : position en degrés (0° à 90°) par incrémentation de 1°.<br/>Bit 116 à 119 : position en minutes (0' à 56') par incrémentation de 4'.<br/>Bit 120 : 0 indique qu'il s'agit d'une longitude Est ; 1 indique qu'il s'agit d'une longitude Ouest.<br/>Bits 121 à 128 : position en degrés (0° à 180°) par incrémentation de 1°.<br/>Bits 129 à 132 : position en minutes (0' à 56') par incrémentation de 4'.<br/>
</td>
</tr>
</tbody>
</table>

</div>

Nota. ― La valeur par défaut pour les bits de 108 à 119 est : 011111110000.

La valeur par défaut pour les bits de 120 à 132 est : 0111111110000.
