# Article 

MODALITÉS DE PRISE EN COMPTE DU SYSTÈME COMBINEO DANS LA RÉGLEMENTATION THERMIQUE 2005

1. Définition du système COMBINEO

Au sens du présent arrêté, le système COMBINEO, modèle 185 LS, est un système compact, capable de réaliser la ventilation, le chauffage et la production d'eau chaude sanitaire. Il fonctionne avec une pompe à chaleur puisant ses calories sur l'air extrait. La production d'eau chaude sanitaire se fait en priorité par rapport au chauffage.

Ce système assure le besoin de régénération de l'air du bâtiment et le besoin de chauffage par ventilation mécanique contrôlée de type double flux thermodynamique.

Une grande partie de l'énergie perdue à travers l'extraction de l'air est récupérée via un échangeur statique et transmise à l'air neuf réinjecté dans le bâtiment.

L'énergie complémentaire nécessaire au maintien en température du bâtiment est apportée par une pompe à chaleur dont le condenseur est placé dans le flux d'air neuf, après l'échangeur statique.

Les besoins supplémentaires de chauffage du bâtiment lors des périodes hivernales fortes (cas de l'insuffisance de la pompe à chaleur) sont générés par un système d'appoint par effet joule piloté par COMBINEO, situé dans les pièces de vie (séjour, salon) et dans les salles de bain, couvrant a minima l'intégralité des déperditions de ces pièces.

COMBINEO assure la production d'eau chaude sanitaire, stockée dans un ballon émaillé.

L'énergie nécessaire au chauffage de l'eau chaude sanitaire est apportée par la pompe à chaleur qui va puiser les calories de l'air extrait du bâtiment à travers un échangeur pour les restituer dans un condenseur au contact du ballon de stockage.

En cas de besoin supplémentaire ponctuel de production d'eau chaude (cas de fort tirage sur une période courte), l'appoint de chauffage de l'eau est réalisé par un élément chauffant électrique direct, intégré au ballon de stockage de COMBINEO.

2. Domaine d'application

Cette méthode s'applique uniquement aux maisons individuelles répondant aux critères suivants :

Surface habitable ≤ 200 m².

Typologies de maison : T3 à T6, avec un débit total extrait ≤ 240 m³/h.

Déperditions par le bâti : Coefficient H<sub>T</sub> (H<sub>T</sub> = Ubat * S<sub>enveloppe</sub>) inférieur ou égal aux valeurs indiquées dans le tableau 1, où :

Ubat représente le coefficient moyen de déperdition par les parois et les baies du bâtiment défini à l'article 15 de l'arrêté du 24 mai 2006 susvisé ;

S<sub>enveloppe</sub> représente la surface totale des parois déperditives du bâtiment.

Tableau 1. Seuils du coefficient H<sub>T max</sub>

<table>
<tbody>
<tr>
<td>
<p align="center">ZONE CLIMATIQUE<br/>
</p>
</td>
<td>
<p align="center">H1</p>
</td>
<td>
<p align="center">H2</p>
</td>
<td>
<p align="center">H3</p>
</td>
</tr>
<tr>
<td align="center">
<p align="left">H<sub>T max</sub> (en W/K)<br/>
</p>
</td>
<td align="center">100<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">120<br/>
</td>
</tr>
</tbody>
</table>

Perméabilité à l'air : Q<sub>4Pa_surf</sub> ≤ 0,60 m³/h/m².

Ambiance régulée par zone de 100 m² maximum.

Zone de bruit BR1 pour les maisons équipées du modèle COMBINEO avec by-pass manuel de l'échangeur.

3. Méthode de prise en compte dans les calculs pour la partie non directement modélisable

La présente méthode propose l'intégration du système COMBINEO, dans la méthode de calcul Th-C-E, en trois phases :

1. Le prétraitement qui permet :

― de calculer la part de chauffage du système COMBINEO et celle de l'appoint (salon + salle de bains), notées β<sub>CH_COMBINEO</sub>, β<sub>CH_appoint_SALON</sub> et β<sub>CH_appoint_SDB</sub>

― de calculer les coefficients correctifs des consommations énergétiques d'ECS et d'auxiliaires de ventilation, notés a<sub>ECS</sub> et a<sub>VENT</sub>

2. Les données à saisir dans la méthode de calcul Th-C-E afin de caractériser le système COMBINEO avec son appoint. Ces données sont issues du prétraitement.

3. Le post-traitement qui permet de corriger les consommations énergétiques d'ECS et d'auxiliaires de ventilation à partir des coefficients aECS et aVENT.

3.1. Prétraitement

La production d'ECS étant prioritaire sur le chauffage, il y a besoin d'une énergie d'appoint pour assurer le chauffage pendant les heures de production d'ECS.

Il est donc nécessaire de déterminer heure par heure la part de chauffage assurée par le système COMBINEO et celle assurée par l'appoint.

3.1.1. Calcul de la part de chauffage assurée par le système COMBINEO et par l'appoint

3.1.1.1. Calcul des déperditions totales du bâtiment

Le calcul du coefficient de déperdition par le bâti s'effectue de la façon suivante :

H<sub>T</sub> = U<sub>bat</sub> × S<sub>enveloppe</sub> (en W/K)

avec :

U<sub>bat</sub> : coefficient moyen de déperdition par transmission à travers les parois déperditives séparant le volume chauffé du bâtiment de l'extérieur, du sol et des locaux non chauffés (en W/[m².K]) ;

S<sub>enveloppe</sub> : surface intérieure totale des parois qui séparent le volume chauffé de l'extérieur, du sol et les locaux non chauffés (en m²).

Le calcul du coefficient de déperdition par le renouvellement d'air du bâtiment s'effectue de la façon suivante :

HV = 0,34 × Qva × (1 ― 0,9 × hECH (en W/K)

avec :

hECH : Efficacité de l'échangeur (en %). Les valeurs sont disponibles dans le tableau 9 ;

Qva : débit spécifique moyen (en m³/h) qui s'exprime sous la forme suivante :

Q<sub>va</sub> = (Q<sub>v_pointe</sub> × D<sub>ugd</sub> + Q<sub>v_base</sub> × (168 ― D<sub>ugd</sub>))/168 (en m³/h)

avec :

D<sub>ugd</sub> : durée d'utilisation en grand débit. Ce coefficient est égal à 7 h/semaine ;

Q<sub>v_pointe</sub> et Q<sub>v_base</sub> : débits de pointe et de base définis selon la typologie du logement (en m³/h).

Le calcul des déperditions totales du bâtiment s'effectue de la façon suivante :

D<sub>(Text)</sub> = (H<sub>T</sub> + H<sub>V</sub>) × (uamb ― uext) (en W)

avec :

HT : coefficient de déperdition par le bâti (en W/K) ;

HV : coefficient de déperdition par le renouvellement d'air du bâtiment (en W/K) ;

uamb : température du local. Ce coefficient est égal à 19 °C en période d'occupation et à 16 °C en période d'inoccupation ;

uext : température extérieure (en °C).

3.1.1.2. Calcul de la puissance PAC chauffage disponible

Lorsqu'il y a production simultanée de chauffage et d'ECS, la PAC utilise en priorité tout ou partie de la puissance totale disponible pour produire l'ECS. Cette part de puissance, bECS_utilisée, s'exprime de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

PECS : puissance du COMBINEO pour la production d'ECS (en W) ;

PECS_utilisée : puissance de la PAC utilisée pour la production d'ECS (en W).

La part de la puissance de la PAC disponible pour la production de chauffage est calculée de la façon suivante :

bCH_dispo = 1 ― bECS_utilisée

avec :

bECS_utilisée : part de la puissance de la PAC utilisée pour la production d'ECS (en %).

Le calcul de la puissance de la PAC disponible pour la production de chauffage s'effectue de la façon suivante :

PCH_dispo = PCH × bCH_dispo (en W)

avec :

PCH : puissance du COMBINEO pour la production de chauffage (en W) ;

bCH_dispo : part de la puissance de la PAC disponible pour la production de chauffage.

3.1.1.3. Calcul de la part de chauffage assurée par l'appoint

Lorsque PCH_dispo D(Text), l'appoint est nul.

Lorsque PCH_dispo ¸ D(Text), le calcul de la puissance de l'appoint nécessaire pour la production de chauffage s'effectue de la façon suivante :

PCH_appoint = D(Text) ― PCH_dispo (en W)

avec :

D(Text) : déperditions totales du bâtiment (en W) ;

PCH_dispo : puissance de la PAC disponible pour le chauffage (en W).

Le calcul de la part de chauffage assurée par l'appoint s'effectue de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

PCH_appoint : puissance de l'appoint nécessaire pour la production de chauffage (en W) ;

D(Text) : déperditions totales du bâtiment (en W).

3.1.1.4. Calcul de la part de chauffage assurée par le système COMBINEO

Le calcul de la part de chauffage assurée par le système COMBINEO s'effectue de la façon suivante :

<sup>β</sup>CH_COMBINEO = 1 ― <sup>β</sup>CH_appoint

avec :

<sup>β</sup>CH_appoint : part de chauffage assurée par l'appoint (en %).

Les mois de juin, juillet, août et septembre sont considérés comme mois de non-chauffe.

3.1.1.5. Répartition du chauffage selon les pièces

Tableau 2. Répartition des parts d'appoint du chauffage selon les pièces

<div align="center">

<table>
<tbody>
<tr>
<td/>
<td>
<p align="center">SALLE DE BAINS<br/>
</p>
</td>
<td>
<p align="center">SALON/SÉJOUR</p>
</td>
<td>
<p align="center">TOUTES LES AUTRES PIÈCES</p>
</td>
</tr>
<tr>
<td align="center">
<p align="left">Type émetteur<br/>
</p>
</td>
<td align="center">Emetteur à effet joule direct<br/>
</td>
<td align="center">Emetteur à effet joule direct<br/>
</td>
<td align="center">COMBINEO<br/>
</td>
</tr>
<tr>
<td align="center">
<p align="left">Répartition<br/>du chauffage<br/>
</p>
</td>
<td align="center">bch_appoint_SDB = SSDB/Shab<br/>SSDB : surface de la salle de bains<br/>Shab : surface habitable<br/>
</td>
<td align="center">
<br/>bch_appoint_SALON = bch_appoint ― bch_appoint_SDB<br/>
</td>
<td align="center">
<br/>bch_COMBINEO<br/>
</td>
</tr>
</tbody>
</table>

</div>

3.1.2. Calcul du coefficient correctif de la consommation énergétique d'ECS

3.1.2.1. Calcul des besoins horaires d'ECS

Le calcul des besoins d'ECS, au pas de temps horaire, s'effectue de la façon suivante :

Qw = rw × Cw × Vuw × (uuw ― ucw) × RatECS (en Wh)

avec :

rw : masse volumique de l'eau, rw = 1 kg/l ;

Cw : capacité calorifique massique de l'eau, Cw = 1,163 Wh/(kg.K) ;

uuw : température de l'eau chaude mitigée utilisée au puisage ;

ucw : température de l'eau froide entrant dans le système de préparation d'eau chaude ;

RatECS : ratio des besoins assurés par le système de production aux besoins totaux de la zone ;

Vuw : volume d'eau chaude mitigée utilisé chaque heure pendant la période normale. Ce coefficient est calculé comme suit :

Vuw = a × ah × Nu (en l)

avec :

a : besoins unitaires exprimés en litres d'eau à 40 °C ;

ah : coefficient horaire de la clé de répartition des besoins d'ECS ;

Nu : nombre d'unités à considérer.

3.1.2.2. Calcul des pertes de distribution

Le calcul des pertes de distribution au pas de temps horaire s'effectue de la façon suivante en considérant la production d'ECS individuelle, dans le volume chauffé :

Qd,w = Qd,w_ind,vc = 0.5 × 0,2 × RatECS × Qw (en Wh)

avec :

Qw : besoins horaires d'ECS (en Wh) ;

RatECS : ratio des besoins d'ECS assurés par le système de production aux besoins totaux d'ECS de la zone.

3.1.2.3. Calcul des pertes de stockage

Le calcul des pertes de stockage au pas de temps horaire s'effectue de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

Vs : volume de stockage (en litre) ;

Cr : constante de refroidissement, Cr = 0,19 Wh/(l.K.jr) ;

uECS : température de stockage, pour le système COMBINEO ce coefficient est égal à 50 °C ;

uamb : température ambiante du local, ce coefficient est égal à 19 °C en période d'occupation et à 16 °C en période d'inoccupation.

3.1.2.4. Calcul des besoins totaux horaires pour la production d'ECS

Le calcul des besoins totaux au pas de temps horaire pour la production d'ECS s'effectue de la façon suivante :

Qecs = Qw + Qd,w + Qg,w (en Wh)

avec :

Qw : besoins horaires d'ECS (en Wh) ;

Qd,w : pertes de distribution horaires (en Wh) ;

Qg,w : pertes de stockage horaires (en Wh).

3.1.2.5. Calcul des consommations énergétiques horaires d'ECS avec le système COMBINEO

Le calcul de la consommation énergétique horaire d'ECS avec le système COMBINEO s'effectue de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

QECS : besoins totaux horaires pour la production d'ECS (en Wh) ;

COPECS : coefficient de performance du système COMBINEO pour la production d'ECS.

3.1.2.6. Calcul du coefficient correctif de la consommation énergétique d'ECS

Le calcul du coefficient de correction de la consommation énergétique d'ECS s'effectue de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

CECS_COMBINEO : consommation énergétique horaire d'ECS avec le système COMBINEO (en Wh) ;

CECS_05 : consommation énergétique d'ECS d'un ballon d'eau chaude électrique (en Wh) dont les caractéristiques techniques sont identiques à celui du COMBINEO avec des pertes de stockage calées sur les règles Th-C-E 2005, à savoir : uECS = 65 °C et uamb = 20 °C.

3.1.3. Calcul du coefficient correctif de la consommation énergétique des auxiliaires de ventilation

Le calcul des consommations énergétiques d'auxiliaires de ventilation se fait comme suit :

― lorsqu'il y a production de chauffage et/ou d'ECS, la puissance des ventilateurs est directement intégrée dans les COPCH et COPECS. Leur consommation énergétique impacte alors les consommations énergétiques de chauffage et/ou d'ECS ;

― lorsqu'il n'y a pas de production de chauffage ni d'ECS, la puissance des ventilateurs est comptabilisée dans la puissance de ventilation et leur consommation énergétique impacte alors la consommation énergétique des auxiliaires de ventilation.

3.1.3.1. Calcul du taux de fonctionnement de la PAC

Le calcul du taux de fonctionnement de la PAC s'effectue de la façon suivante :

Vous pouvez consulter le tableau dans le JO n° 292 du 17/12/2011 texte numéro 7

avec :

PECS_utilisée : puissance de la PAC utilisée pour la production d'ECS (en W) ;

PECS : puissance du COMBINEO pour la production d'ECS (en W) ;

PCH_utilisée : puissance de la PAC utilisée pour le chauffage (en W) ;

PCH : puissance du COMBINEO pour la production de chauffage (en W).

3.1.3.2. Calcul du coefficient correctif de la consommation énergétique des auxiliaires de ventilation

Le calcul du coefficient de correction de la consommation énergétique des auxiliaires de ventilation s'effectue de la façon suivante :

aVENT = 1 ― aPAC

avec :

aPAC : taux de fonctionnement de la PAC.

3.2. Intégration du système COMBINEO dans Th-C-E

L'intégration du système COMBINEO dans la méthode Th-C-E s'effectue de la façon suivante :

3.2.1. Génération de chauffage

Une génération pour le COMBINEO : Système thermodynamique Air rejeté/Air extérieur, COPCH non certifié, avec régulation en Tout Ou Rien.

Une génération pour l'appoint effet joule : système effet joule direct, saisi conformément aux règles Th-C-E.

3.2.2. Emission de chauffage

Dans la méthode de calcul Th-C-E, trois émissions de chauffage sont créées :

1 pour le COMBINEO suivant le tableau 3 ;

1 pour l'appoint dans le salon/séjour suivant le tableau 4 ;

1 pour l'appoint dans les salles de bains suivant le tableau 5.

Par défaut, les caractéristiques des émetteurs de chaleur correspondent aux valeurs définies par défaut dans les règles Th-C-E.

Tableau 3. Description de l'émetteur 1 par soufflage d'air chaud du COMBINEO

<div align="center">

<table>
<tbody>
<tr>
<td colspan="2">
<p align="center">ÉMETTEUR 1 - SOUFFLAGE D'AIR CHAUD (COMBINEO)</p>
</td>
</tr>
<tr>
<td align="center">Type d'émetteur<br/>
</td>
<td align="center">Chauffage seul<br/>
</td>
</tr>
<tr>
<td align="center">Ventilateurs liés aux émetteurs<br/>
</td>
<td align="center">Pas de ventilateur<br/>
</td>
</tr>
<tr>
<td align="center">Puissance des ventilateurs<br/>
</td>
<td align="center">―<br/>
</td>
</tr>
<tr>
<td align="center">Perte au dos des émetteurs<br/>
</td>
<td align="center">―<br/>
</td>
</tr>
<tr>
<td align="center">Surface<br/>
</td>
<td align="center">Surface totale (Shab)<br/>
</td>
</tr>
<tr>
<td align="center">Hauteur sous plafond<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
</tr>
<tr>
<td align="center">Type de chauffage<br/>
</td>
<td align="center">Electrique autre (thermodynamique)<br/>
</td>
</tr>
<tr>
<td align="center">Type d'émetteur chaud<br/>
</td>
<td align="center">Air soufflé<br/>
</td>
</tr>
<tr>
<td align="center">Lien avec la génération<br/>
</td>
<td align="center">Génération 1 : COMBINEO<br/>
</td>
</tr>
<tr>
<td align="center">Part de besoin assurée par ce système<br/>
</td>
<td align="center">bCH_COMBINEO<br/>
</td>
</tr>
<tr>
<td align="center">Variation spatiale<br/>
</td>
<td align="center">Classe B<br/>
</td>
</tr>
<tr>
<td align="center">Variation temporelle<br/>
</td>
<td align="center">Couple régulateur-émetteur permettant l'arrêt total de l'émission<br/>
</td>
</tr>
<tr>
<td align="center">Lien vers CTA à débit variable<br/>
</td>
<td align="center">Pas de lien<br/>
</td>
</tr>
<tr>
<td align="center">Réseau chaud<br/>
</td>
<td align="center">Inexistant ou pertes nulles<br/>
</td>
</tr>
</tbody>
</table>

</div>

Tableau 4. Description de l'émetteur 2 par effet joule dans le salon/séjour

<div align="center">

<table>
<tbody>
<tr>
<th colspan="4">ÉMETTEUR 2 - APPOINT SALON/SÉJOUR<br/>
</th>
</tr>
<tr>
<td align="center">Type d'émetteur<br/>
</td>
<td align="center">Chauffage seul<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Ventilateurs liés aux émetteurs<br/>
</td>
<td align="center">Pas de ventilateur<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Puissance des ventilateurs<br/>
</td>
<td align="center">―<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Perte au dos des émetteurs<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Surface<br/>
</td>
<td align="center">Surface totale (Shab)<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Hauteur sous plafond<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Type de chauffage<br/>
</td>
<td align="center">Electrique direct<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Type d'émetteur chaud<br/>
</td>
<td align="center">PRE ou panneau rayonnant ou convecteur<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Lien avec la génération<br/>
</td>
<td align="center">Génération 2 - appoint par effet joule<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Part de besoin assurée par ce système<br/>
</td>
<td align="center">bCH_appoint_SALON<br/>
</td>
<td align="center">
<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Variation spatiale<br/>
</td>
<td align="center">Classe A si PRE<br/>
</td>
<td align="center">Classe B<br/>si panneau rayonnant<br/>
</td>
<td align="center">Classe C si convecteur<br/>
</td>
</tr>
<tr>
<td align="center">Variation temporelle<br/>
</td>
<td align="center">Couple régulateur/émetteur<br/>permettant l'arrêt total<br/>de l'émission<br/>ou<br/>valeur connue si variation<br/>temporelle certifiée<br/>
</td>
<td align="center">Emetteur électrique direct avec thermostat intégré certifié<br/>ou<br/>valeur connue si variation temporelle certifiée<br/>
</td>
</tr>
</tbody>
</table>

</div>

Tableau 5. Description de l'émetteur 3 par effet joule dans les salles de bains

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">ÉMETTEUR 3 - APPOINT SALLES DE BAINS<br/>
</th>
</tr>
<tr>
<td align="center">Type d'émetteur<br/>
</td>
<td align="center">Chauffage seul<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Ventilateurs liés aux émetteurs<br/>
</td>
<td align="center">Pas de ventilateur<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Puissance des ventilateurs<br/>
</td>
<td align="center">―<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Perte au dos des émetteurs<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Surface<br/>
</td>
<td align="center">Surface totale (Shab)<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Hauteur sous plafond<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Type de chauffage<br/>
</td>
<td align="center">Electrique direct<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Type d'émetteur chaud<br/>
</td>
<td align="center">Panneau rayonnant ou convecteur<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Lien avec la génération<br/>
</td>
<td align="center">Génération 2 - appoint par effet joule<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Part de besoin assurée par ce système<br/>
</td>
<td align="center">bCH_appoint_SDB<br/>
</td>
<td align="center">
<br/>
</td>
</tr>
<tr>
<td align="center">Variation spatiale<br/>
</td>
<td align="center">Classe B si panneau rayonnant<br/>
</td>
<td align="center">Classe C si convecteur<br/>
</td>
</tr>
<tr>
<td align="center">Variation temporelle<br/>
</td>
<td align="center">Emetteur électrique direct avec thermostat intégré certifié<br/>ou<br/>valeur connue si variation temporelle certifiée<br/>
</td>
</tr>
</tbody>
</table>

</div>

3.2.3. Production d'ECS

La production d'ECS est modélisée dans la méthode de calcul Th-C-E par un ballon électrique de capacité et de performances équivalentes au ballon du COMBINEO, à savoir :

Volume du ballon : 185 L

Constante de refroidissement : Cr = 0.19 Wh/l.K.jr

3.2.4. Ventilation

Le système de ventilation est modélisé dans la méthode de calcul Th-C-E par une ventilation mécanique contrôlée de type double flux thermodynamique avec les caractéristiques détaillées dans les tableaux 6 et 7 suivants :

Tableau 6. Description de la CTA

<div align="center">

<table>
<tbody>
<tr>
<th colspan="2">CENTRALE DE TRAITEMENT D'AIR - DF COMBINEO<br/>
</th>
</tr>
<tr>
<td align="center">Type de ventilation<br/>
</td>
<td align="center">Double flux hygiénique<br/>
</td>
</tr>
<tr>
<td align="center">Puissance des ventilateurs en occupation<br/>
</td>
<td align="center">PVENT<br/>
</td>
</tr>
<tr>
<td align="center">Type de réseau aéraulique<br/>
</td>
<td align="center">Autre cas et type par défaut, classe C<br/>
</td>
</tr>
<tr>
<td align="center">Présence de filtres de classe F5 à F9<br/>
</td>
<td align="center">Oui<br/>
</td>
</tr>
<tr>
<td align="center">Présence d'un échangeur<br/>
</td>
<td align="center">Oui<br/>
</td>
</tr>
<tr>
<td align="center">Efficacité de l'échangeur<br/>
</td>
<td align="center">bECH<br/>
</td>
</tr>
<tr>
<td align="center">Valeur certifiée<br/>
</td>
<td align="center">Non<br/>
</td>
</tr>
<tr>
<td align="center">Puissance électrique des auxiliaires<br/>
</td>
<td align="center">0 W<br/>
</td>
</tr>
<tr>
<td align="center">Bypassage de l'échangeur<br/>
</td>
<td align="center">Arrêt manuel ou automatique de l'échangeur hors période de chauffage<br/>
</td>
</tr>
<tr>
<td align="center">Génération associée à l'antigel<br/>
</td>
<td align="center">Pas de lien<br/>
</td>
</tr>
</tbody>
</table>

</div>

Tableau 7. Description de la ventilation

<div align="center">

<table>
<tbody>
<tr>
<th colspan="2">VENTILATION<br/>
</th>
</tr>
<tr>
<td align="center">Description des logements<br/>
</td>
<td align="center">Propre au projet<br/>
</td>
</tr>
<tr>
<td align="center">Type de ventilation<br/>
</td>
<td align="center">Ventilation mécanique double flux<br/>
</td>
</tr>
<tr>
<td align="center">Lien vers la CTA<br/>
</td>
<td align="center">Centrale de traitement d'air ― DF COMBINEO<br/>
</td>
</tr>
<tr>
<td align="center">Composant de ventilation : Cdep<br/>
</td>
<td align="center">Autoréglable<br/>
</td>
</tr>
<tr>
<td align="center">Gestion de la ventilation<br/>
</td>
<td align="center">Dispositif avec temporisateur<br/>
</td>
</tr>
</tbody>
</table>

</div>

Les données de sortie issues du prétraitement qui doivent être saisies dans la méthode de calcul Th-C-E sont définies dans le tableau 8 suivant :

Tableau 8. Données issues du prétraitement à saisir dans la méthode Th-C-E

<div align="center">

<table>
<tbody>
<tr>
<th>PARTIES DE Th-C-E<br/>à alimenter<br/>
</th>
<th>DÉNOMINATION<br/>
</th>
<th>DONNÉES À SAISIR<br/>pour caractériser<br/>le système COMBINEO<br/>
</th>
</tr>
<tr>
<td align="center">Production de chauffage<br/>
</td>
<td align="center">Puissance nominale<br/>
</td>
<td align="center">PCH<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">COP nominal<br/>
</td>
<td align="center">COPCH<br/>
</td>
</tr>
<tr>
<td align="center">Emetteurs de chauffage<br/>
</td>
<td align="center">Part de besoin assurée par COMBINEO<br/>
</td>
<td align="center">bCH_COMBINEO<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">Part de besoin assurée par l'appoint salon/séjour<br/>
</td>
<td align="center">bCH_appoint_SALON<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">Part de besoin assurée par l'appoint salle de bains<br/>
</td>
<td align="center">bCH_appoint_SDB<br/>
</td>
</tr>
<tr>
<td align="center">Ventilation<br/>
</td>
<td align="center">Puissance des ventilateurs en occupation<br/>
</td>
<td align="center">PVENT<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">Efficacité de l'échangeur<br/>
</td>
<td align="center">hECH<br/>
</td>
</tr>
</tbody>
</table>

</div>

3.3. Post-traitement

Le calcul de la consommation énergétique d'ECS du projet utilisant le système COMBINEO s'effectue de la façon suivante :

CECS_projet = CEP-ECS × aECS (en kWhEP/[m².an])

avec :

CEPS-ECS : consommation énergétique d'ECS déterminée selon la méthode de calcul Th-C-E intégrant le système COMBINEO (en kWhEP/[m².an]) ;

aECS : coefficient de correction de la consommation énergétique d'ECS.

Le calcul de la consommation énergétique des auxiliaires de ventilation du projet utilisant le système COMBINEO (CAUX_VENT_projet) s'effectue de la façon suivante :

CAUX_VENT_projet = CEP_AUX_VENT × aVENT (en kWhEP/[m².an])

avec :

CEP_AUX_VENT : consommation énergétique des auxiliaires de ventilation déterminée selon la méthode de calcul Th-C-E intégrant le système COMBINEO (en kWhEP/[m².an]) ;

aVENT : coefficient de correction de la consommation énergétique des auxiliaires de ventilation.

3.4. Données techniques

3.1.1. Caractéristiques du COMBINEO

Le tableau 9 ci-dessous fournit les puissances et COP disponibles (ECS et chauffage) et les données de ventilation (PVENT et hECH) pour différentes conditions de températures extérieures (de ― 15 °C à 40 °C) et de débits de ventilation (95, 150 et 240 m³/h).

Les caractéristiques du COMBINEO correspondant à des conditions de fonctionnement (T° et/ou débit) intermédiaires à celles détaillés dans le tableau 9 ci-dessous, peuvent être déterminées par inter et extrapolation.

Tableau 9. Données caractéristiques du COMBINEO 185 LS

<div align="center">

<table>
<tbody>
<tr>
<th>
<br/>DÉBIT D'AIR<br/>
</th>
<th>
<br/>T° AIR<br/>extérieur<br/>(°C)<br/>
</th>
<th>PUISSANCE<br/>électrique<br/>de ventilateur :<br/>PVENT (W)<br/>
</th>
<th>EFFICACITÉ<br/>échangeur<br/>hECH (%)<br/>
</th>
<th>PUISSANCE<br/>électrique<br/>compresseur<br/>(W)<br/>
</th>
<th colspan="2">FONCTIONNEMENT ECS<br/>
</th>
<th>FONCTIONNEMENT<br/>chauffage<br/>
</th>
<th/>
<th/>
<th>PECS (W)<br/>
</th>
<th>COPECS<br/>
</th>
<th>PCH (W)<br/>
</th>
<th>COPCH<br/>
</th>
</tr>
<tr>
<td align="center">95 m³/h<br/>
</td>
<td align="center">― 15<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">658<br/>
</td>
<td align="center">1,24<br/>
</td>
<td align="center">811<br/>
</td>
<td align="center">1,52<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 10<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">717<br/>
</td>
<td align="center">1,35<br/>
</td>
<td align="center">869<br/>
</td>
<td align="center">1,63<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 5<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">775<br/>
</td>
<td align="center">1,46<br/>
</td>
<td align="center">927<br/>
</td>
<td align="center">1,74<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">834<br/>
</td>
<td align="center">1,57<br/>
</td>
<td align="center">986<br/>
</td>
<td align="center">1,85<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">5<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">892<br/>
</td>
<td align="center">1,68<br/>
</td>
<td align="center">1 044<br/>
</td>
<td align="center">1,96<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">10<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">950<br/>
</td>
<td align="center">1,79<br/>
</td>
<td align="center">1 103<br/>
</td>
<td align="center">2,07<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">15<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 009<br/>
</td>
<td align="center">1,90<br/>
</td>
<td align="center">1 161<br/>
</td>
<td align="center">2,18<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">20<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 067<br/>
</td>
<td align="center">2,01<br/>
</td>
<td align="center">1 219<br/>
</td>
<td align="center">2,29<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">25<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 125<br/>
</td>
<td align="center">2,12<br/>
</td>
<td align="center">1 278<br/>
</td>
<td align="center">2,40<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">30<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 184<br/>
</td>
<td align="center">2,22<br/>
</td>
<td align="center">1 336<br/>
</td>
<td align="center">2,51<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">35<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 242<br/>
</td>
<td align="center">2,33<br/>
</td>
<td align="center">1 394<br/>
</td>
<td align="center">2,62<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">40<br/>
</td>
<td align="center">50<br/>
</td>
<td align="center">89,8 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 300<br/>
</td>
<td align="center">2,44<br/>
</td>
<td align="center">1 453<br/>
</td>
<td align="center">2,73<br/>
</td>
</tr>
<tr>
<td align="center">150 m³/h<br/>
</td>
<td align="center">― 15<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">464<br/>
</td>
<td align="center">0,85<br/>
</td>
<td align="center">868<br/>
</td>
<td align="center">1,59<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 10<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">590<br/>
</td>
<td align="center">1,08<br/>
</td>
<td align="center">994<br/>
</td>
<td align="center">1,82<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 5<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">716<br/>
</td>
<td align="center">1,31<br/>
</td>
<td align="center">1 120<br/>
</td>
<td align="center">2,05<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">842<br/>
</td>
<td align="center">1,54<br/>
</td>
<td align="center">1 246<br/>
</td>
<td align="center">2,29<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">5<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">968<br/>
</td>
<td align="center">1,78<br/>
</td>
<td align="center">1 372<br/>
</td>
<td align="center">2,52<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">10<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 094<br/>
</td>
<td align="center">2,01<br/>
</td>
<td align="center">1 498<br/>
</td>
<td align="center">2,75<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">15<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 220<br/>
</td>
<td align="center">2,24<br/>
</td>
<td align="center">1 624<br/>
</td>
<td align="center">2,98<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">20<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 347<br/>
</td>
<td align="center">2,47<br/>
</td>
<td align="center">1 751<br/>
</td>
<td align="center">3,21<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">25<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 473<br/>
</td>
<td align="center">2,70<br/>
</td>
<td align="center">1 877<br/>
</td>
<td align="center">3,44<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">30<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 599<br/>
</td>
<td align="center">2,93<br/>
</td>
<td align="center">2 003<br/>
</td>
<td align="center">3,68<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">35<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 725<br/>
</td>
<td align="center">3,17<br/>
</td>
<td align="center">2 129<br/>
</td>
<td align="center">3,91<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">40<br/>
</td>
<td align="center">55<br/>
</td>
<td align="center">89,4 %<br/>
</td>
<td align="center">490<br/>
</td>
<td align="center">1 851<br/>
</td>
<td align="center">3,40<br/>
</td>
<td align="center">2 255<br/>
</td>
<td align="center">4,14<br/>
</td>
</tr>
<tr>
<td align="center">240 m³/h<br/>
</td>
<td align="center">― 15<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">104<br/>
</td>
<td align="center">0,18<br/>
</td>
<td align="center">607<br/>
</td>
<td align="center">1,02<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 10<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">321<br/>
</td>
<td align="center">0,54<br/>
</td>
<td align="center">824<br/>
</td>
<td align="center">1,39<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">― 5<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">538<br/>
</td>
<td align="center">0,91<br/>
</td>
<td align="center">1 040<br/>
</td>
<td align="center">1,76<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">0<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">755<br/>
</td>
<td align="center">1,27<br/>
</td>
<td align="center">1 257<br/>
</td>
<td align="center">2,12<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">5<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">971<br/>
</td>
<td align="center">1,64<br/>
</td>
<td align="center">1 474<br/>
</td>
<td align="center">2,49<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">10<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 188<br/>
</td>
<td align="center">2,01<br/>
</td>
<td align="center">1 691<br/>
</td>
<td align="center">2,86<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">15<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 405<br/>
</td>
<td align="center">2,37<br/>
</td>
<td align="center">1 907<br/>
</td>
<td align="center">3,22<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">20<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 622<br/>
</td>
<td align="center">2,74<br/>
</td>
<td align="center">2 124<br/>
</td>
<td align="center">3,59<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">25<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">1 838<br/>
</td>
<td align="center">3,11<br/>
</td>
<td align="center">2 341<br/>
</td>
<td align="center">3,95<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">30<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">2 055<br/>
</td>
<td align="center">3,47<br/>
</td>
<td align="center">2 558<br/>
</td>
<td align="center">4,32<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">35<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">2 272<br/>
</td>
<td align="center">3,84<br/>
</td>
<td align="center">2 774<br/>
</td>
<td align="center">4,69<br/>
</td>
</tr>
<tr>
<td align="center">
<br/>
</td>
<td align="center">40<br/>
</td>
<td align="center">110<br/>
</td>
<td align="center">88,0 %<br/>
</td>
<td align="center">482<br/>
</td>
<td align="center">2 489<br/>
</td>
<td align="center">4,20<br/>
</td>
<td align="center">2 991<br/>
</td>
<td align="center">5,05<br/>
</td>
</tr>
</tbody>
</table>

</div>

3.1.2. Données de ventilation liées à la typologie de bâtiment

Il est possible de renseigner les débits de ventilation (base et pointe) par deux moyens :

― en les renseignant directement si les valeurs sont connues ;

― en se référant au tableau 10 ci-dessous, selon le type de logement :

Tableau 10. Débits réglementaires selon la typologie

<div align="center">

<table>
<tbody>
<tr>
<th>TYPOLOGIE<br/>
</th>
<th>DÉBIT BASE (m³/h)<br/>
</th>
<th>DÉBIT POINTE (m³/h)<br/>
</th>
</tr>
<tr>
<td align="center">T3 1 SDB 1 WC<br/>
</td>
<td align="center">90<br/>
</td>
<td align="center">150<br/>
</td>
</tr>
<tr>
<td align="center">T3 1 SDB 2 WC<br/>
</td>
<td align="center">105<br/>
</td>
<td align="center">165<br/>
</td>
</tr>
<tr>
<td align="center">T3 2 SDB 1 WC<br/>
</td>
<td align="center">120<br/>
</td>
<td align="center">180<br/>
</td>
</tr>
<tr>
<td align="center">T3 2 SDB 2 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">195<br/>
</td>
</tr>
<tr>
<td align="center">T4 1 SDB 1 WC<br/>
</td>
<td align="center">105<br/>
</td>
<td align="center">180<br/>
</td>
</tr>
<tr>
<td align="center">T4 1 SDB 2 WC<br/>
</td>
<td align="center">105<br/>
</td>
<td align="center">180<br/>
</td>
</tr>
<tr>
<td align="center">T4 2 SDB 1 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">210<br/>
</td>
</tr>
<tr>
<td align="center">T4 2 SDB 2 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">210<br/>
</td>
</tr>
<tr>
<td align="center">T5 1 SDB 1 WC<br/>
</td>
<td align="center">105<br/>
</td>
<td align="center">195<br/>
</td>
</tr>
<tr>
<td align="center">T5 1 SDB 2 WC<br/>
</td>
<td align="center">105<br/>
</td>
<td align="center">195<br/>
</td>
</tr>
<tr>
<td align="center">T5 2 SDB 1 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">225<br/>
</td>
</tr>
<tr>
<td align="center">T5 2 SDB 2 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">225<br/>
</td>
</tr>
<tr>
<td align="center">T6 2 SDB 1 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">225<br/>
</td>
</tr>
<tr>
<td align="center">T6 2 SDB 2 WC<br/>
</td>
<td align="center">135<br/>
</td>
<td align="center">225<br/>
</td>
</tr>
<tr>
<td align="center">Cellier<br/>
</td>
<td align="center">―<br/>
</td>
<td align="center">15<br/>
</td>
</tr>
</tbody>
</table>

</div>

3.1.3. Corrections de la température extérieure en fonction de l'altitude

Tableau 11. Correction de la température extérieure selon l'altitude

<div align="center">

<table>
<tbody>
<tr>
<th>ALTITUDE (m)<br/>
</th>
<th colspan="2">CORRECTION T° EXT. (°C)<br/>
</th>
</tr>
<tr>
<td align="center">Alt 400 m<br/>
</td>
<td align="center">0<br/>
</td>
</tr>
<tr>
<td align="center">400 m ¸ Alt 800 m<br/>
</td>
<td align="center">― 2<br/>
</td>
</tr>
<tr>
<td align="center">Alt ¹ 800 m<br/>
</td>
<td align="center">― 4<br/>
</td>
</tr>
</tbody>
</table>

</div>
