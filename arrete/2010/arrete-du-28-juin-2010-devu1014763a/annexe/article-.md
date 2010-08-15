# Article 

MODALITÉS DE PRISE EN COMPTE DU SYSTÈME HÉLIOPAC DANS LA RÉGLEMENTATION THERMIQUE POUR LES BÂTIMENTS EXISTANTS

1. Définition du système Héliopac

Au sens du présent arrêté, le système Héliopac permet de produire de l'eau chaude sanitaire en couplant un capteur solaire non vitré de marque Solerpool à une pompe à chaleur eau-eau de marque Solerpac.

Le système est associé à un appoint qui permet de compenser la diminution de la puissance de la pompe à chaleur par temps froid et d'assurer un relais complet en dessous de ― 5° C extérieur.

2. Domaine d'application

Cette méthode s'applique uniquement aux immeubles collectifs d'habitations, aux bâtiments hôteliers et d'hébergement qui respectent les conditions suivantes :

― des besoins annuels compris entre 1 000 m³ et 12 500 m³ d'eau chaude sanitaire à 40 °C ;

― un nombre de pompes à chaleur inférieur à 6 ;

― des capteurs solaires non vitrés implantés avec un angle d'inclinaison par rapport au plan horizontal inférieur à 15° et dont la surface est comprise entre 30 m² et 100 m² par pompe à chaleur ;

― une distance maximale de 20 m entre la pompe à chaleur et le ballon d'eau chaude sanitaire le plus éloigné ;

― une altitude maximale du bâtiment de 400 m.

3. Méthode de prise en compte dans les calculs pour la partie non directement modélisable

La présente méthode propose l'intégration du système Héliopac comme suit :

― modéliser le système Héliopac, dans la méthode de calcul Th-C-E ex, comme un générateur collectif classique en saisissant uniquement l'appoint sans pertes de stockage ;

― corriger la consommation d'eau chaude sanitaire en énergie finale ainsi obtenue (Cecs ef) par le moteur de calcul par la performance globale annuelle du système (Pgs) pour la part assurée par le système Héliopac.

Le coefficient Pgs prend en compte les consommations énergétiques de la PAC, celles de l'appoint, des pompes et l'ensemble des pertes thermiques des ballons.

3.1. Détermination du coefficient de performance globale annuelle du système (Pgs)

Le coefficient de performance globale annuelle du système est déterminé à partir d'un des deux tableaux ci-dessous (tableaux 1 et 2) qui se différencient suivant l'usage du bâtiment (immeuble collectif d'habitations ou bâtiment d'hébergement et bâtiment hôtelier).

Les données du projet nécessaires à la détermination de ce coefficient sont :

― la zone climatique ;

― le besoin en eau chaude sanitaire annuel (en m³/an à 40 °C) divisé par le nombre de pompes à chaleur Solerpac du projet ;

― la surface effective de capteurs solaires retenue pour le projet divisé par le nombre de pompes à chaleur Solerpac du projet.

La surface effective de capteurs solaires retenue pour le projet correspond à la surface totale des capteurs amputée des zones d'ombrage éventuelles. Les zones d'ombrage sont définies comme les parties du capteur sur lesquelles un obstacle sur les directions EST/SUD/OUEST apparaît avec une hauteur de plus de 45°.

Vous pouvez consulter le tableau dans le JO

n° 187 du 14/08/2010 texte numéro 1

Si les valeurs de besoin en eau chaude sanitaire ou celles de la surface effective du projet ne correspondent pas aux valeurs proposées dans les deux tableaux, on obtient les valeurs de Pgs et de Papp par une interpolation linéaire entre deux lignes et/ou entre deux colonnes.

3.2. Saisie du générateur collectif d'eau chaude sanitaire dans le moteur de calcul Th-C-E ex

Le système de génération à considérer dans le moteur de calcul Th-C-E ex est celui de l'appoint seul, avec une constante de refroidissement (Cr) des ballons de stockage prise égale à zéro.

Le système utilisé dans le moteur de calcul Th-C-E ex pour calculer la consommation d'énergie du bâtiment de référence est défini dans le titre II de l'arrêté du 13 juin 2008 et correspond au générateur prévu pour l'appoint.

3.3. Post-traitement pour l'intégration dans le moteur de calcul Th-C-E ex

La consommation d'ECS en énergie primaire du système "Héliopac + appoint" est définie par la formule suivante :

Vous pouvez consulter le tableau dans le JO

n° 187 du 14/08/2010 texte numéro 1

où :

C ecs ef : consommation d'ECS en énergie finale du projet ;

Pgs : performance globale annuelle du système Héliopac ;

Papp : part du besoin produit par l'appoint (en %). Ce coefficient est déterminé à partir de la zone climatique du projet, de la surface de capteurs solaires et du besoin d'eau chaude sanitaire.Les tableaux 1 et 2 donnent les valeurs de ce coefficient ;

C tep : coefficient de transformation en énergie primaire de l'énergie d'appoint défini par l'article 41 de l'arrêté du 13 juin 2008 susvisé.

Les corrections à apporter à la consommation d'énergie primaire du projet sont les suivantes :

Vous pouvez consulter le tableau dans le JO

n° 187 du 14/08/2010 texte numéro 1

où :

C ep : consommation en énergie primaire du projet ;

C ecs Héliopac : consommation d'ECS en énergie primaire du système "Héliopac + appoint" ;

C ecs : consommation d'ECS en énergie primaire du projet.
