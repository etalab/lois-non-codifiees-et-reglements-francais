# Article Annexe

MODALITÉS DE PRISE EN COMPTE DU SYSTÈME HÉLIOPAC DANS LA RÉGLEMENTATION THERMIQUE 2005

1. Définition du système Héliopac

Au sens du présent arrêté, le système Héliopac permet de produire de l'eau chaude sanitaire en couplant un capteur solaire non vitré de marque Solerpool à une pompe à chaleur eau-eau de marque Solerpac.

Le système est associé à un appoint qui permet de compenser la diminution de la puissance de la pompe à chaleur par temps froid et d'assurer un relais complet en dessous de ― 5 °C extérieur.

2. Domaine d'application

Cette méthode s'applique uniquement aux immeubles collectifs d'habitations et aux bâtiments hôteliers qui respectent les conditions suivantes :

― des besoins annuels compris entre 1 000 m³ et 12 500 m³ d'eau chaude sanitaire à 40 °C ;

― un nombre de pompes à chaleur inférieur à 6 ;

― des capteurs solaires non vitrés implantés avec un angle d'inclinaison par rapport au plan horizontal inférieur à 15° et dont la surface est comprise entre 30 m² et 100 m² par pompe à chaleur ;

― une distance maximale de 20 m entre la pompe à chaleur et le ballon d'eau chaude sanitaire le plus éloigné ;

― une altitude maximale du bâtiment de 400 m.

3. Méthode de prise en compte dans les calculs pour la partie non directement modélisable

La présente méthode propose l'intégration du système Héliopac comme suit :

― modéliser le système Héliopac, dans la méthode de calcul Th-C-E, comme un générateur collectif classique en saisissant uniquement l'appoint sans pertes de stockage ;

― corriger la consommation d'eau chaude sanitaire en énergie primaire ainsi obtenue (Cecs) par le moteur de calcul par la performance globale annuelle du système (Pgs) pour la part assurée par le système Héliopac.

Le coefficient Pgs prend en compte les consommations énergétiques de la PAC, celles de l'appoint, des pompes et l'ensemble des pertes thermiques des ballons.

3.1. Détermination du coefficient de performance globale annuelle du système (Pgs)

Le coefficient de performance globale annuelle du système est déterminé à partir d'un des deux tableaux ci-dessous (tableaux 1 et 2) qui se différencient suivant l'usage du bâtiment (immeuble collectif d'habitations et bâtiment hôtelier).

Les données du projet nécessaires à la détermination de ce coefficient sont :

― la zone climatique ;

― le besoin en eau chaude sanitaire annuel (en m³/an à 40 °C) divisé par le nombre de pompes à chaleur Solerpac du projet ;

― la surface effective de capteurs solaires retenue pour le projet divisé par le nombre de pompes à chaleur Solerpac du projet.

La surface effective de capteurs solaires retenue pour le projet correspond à la surface totale des capteurs amputée des zones d'ombrage éventuelles. Les zones d'ombrage sont définies comme les parties du capteur sur lesquelles un obstacle sur les directions EST/SUD/OUEST apparaît avec une hauteur de plus de 45°.

Vous pouvez consulter les tableaux dans le JO n° 59 du 11/03/2010 texte numéro 5

Si les valeurs de besoin en eau chaude sanitaire ou celles de la surface effective du projet ne correspondent pas aux valeurs proposées dans les deux tableaux, on obtient les valeurs de Pgs et de Papp par une interpolation linéaire entre deux lignes et/ou entre deux colonnes.

3.2. Saisie du générateur collectif d'eau chaude sanitaire dans le moteur de calcul Th-C-E

Le système de génération à considérer dans le moteur de calcul Th-C-E est celui de l'appoint seul, avec une constante de refroidissement (Cr) des ballons de stockage prise égale à zéro.

Le système utilisé dans le moteur de calcul Th-C-E pour calculer la consommation d'énergie du bâtiment de référence est défini dans le titre II de l'arrêté du 24 mai 2006 susvisé et correspond au générateur prévu pour l'appoint.

3.3. Post-traitement pour l'intégration dans le moteur de calcul Th-C-E

La consommation d'ECS en énergie primaire du système  Héliopac + appoint  est définie la formule suivante :

Cecs Héliopac = Cecs /Pgs* (1 ― Papp) + Papp* Cecs

où :

Cecs : consommation d'ECS en énergie primaire du projet.

Pgs : performance globale annuelle du système Héliopac.

Papp : part du besoin produit par l'appoint (en %). Ce coefficient est déterminé à partir de la zone climatique du projet, de la surface de capteurs solaires et du besoin d'eau chaude sanitaire. Les tableaux 1 et 2 donnent les valeurs de ce coefficient.

Les corrections à apporter à la consommation énergétique d'ECS du projet sont les suivantes :

Cep corrigé = Cep ― Cecs + Cecs Héliopac

où :

Cep : consommation en énergie primaire du projet.

Cecs : consommation d'ECS en énergie primaire du projet.
