# Article Annexe

Cette annexe présente une structure pour la transmission des données mentionnées au II de l'article D. 98-6-3 du code des postes et des communications électroniques, conformément au V du même article. Les infrastructures de génie civil, nœuds de réseau et équipements passifs présentés sont chacun décrits par des attributs. L'opérateur ou le gestionnaire d'infrastructures fournit l'information relative aux attributs marqués d'un astérisque (*) lorsqu'il en dispose et peut la fournir sans effectuer un traitement excessivement complexe.

I. - Infrastructures d'accueil des réseaux de communications électroniques

1. Artère de génie civil

Une artère de génie civil est une infrastructure aérienne ou souterraine accueillant des câbles utilisés pour les réseaux de communications électroniques. Les câbles déployés directement en pleine terre, sans fourreau ou sans protection ne constituent pas des artères de génie civil au sens du présent arrêté.

Attributs :

- identifiant ;

- nature ;

- tracé ;

- occupation*.

Nature : l'opérateur ou le gestionnaire d'infrastructures distingue a minima les artères aériennes et souterraines. Il fournit les informations dont il dispose pour distinguer, par exemple, les artères souterraines en conduite rigide, les artères aériennes sur poteaux en propre, les traverses sur pylônes électriques, les artères aériennes en façade...

Occupation : l'information dont dispose l'opérateur peut être présentée sous les formes suivantes :

- nombre de câbles pouvant encore être déployés sur la base d'un câble de diamètre moyen de l'ordre de 16 mm ;

- saturation de l'artère ;

- nombre d'ancrages de câbles pouvant encore être supportés sur les traverses pour les artères aériennes sur pylône.

2. Chambre

Une chambre est une infrastructure de génie civil localisée sur une artère souterraine et permettant d'accéder aux alvéoles et équipements déployés dans cette artère.

Attributs :

- identifiant ;

- type ;

- position* ;

- état de la chambre* ;

- accès* ;

- occupation*.

Type : lorsque cela est pertinent, le type de chambre est décrit en utilisant la norme NF P98-050-1 d'avril 2006 relative aux ouvrages souterrains de télécommunications pour les zones de circulation utilisées par les piétons et les véhicules.

Position : la position est déterminée par les coordonnées géographiques de la chambre.

Etat de la chambre : il est indiqué si la chambre est existante, projetée ou abandonnée, c'est-à-dire hors d'usage.

Accès : il est indiqué si la chambre est ou n'est pas sécurisée et l'endroit où celle-ci est située (par exemple sous-chaussée, sous-trottoir...).

Occupation : l'information dont dispose l'opérateur peut être indiquée sous les formes suivantes :

- équipements présents dans la chambre ;

- équipements pouvant être installés dans la chambre ;

- évaluation du taux d'occupation (0 %, 25 %, 50 %, 75 %, 100 %) ;

- saturation de la chambre.

3. Alvéole

Une alvéole désigne un équipement, par exemple un fourreau, déployé dans une artère souterraine entre deux chambres ou entre une chambre et une propriété desservie pour protéger ou faciliter le déploiement de câbles.

Attributs :

- identifiant ;

- identifiant artère ;

- identifiant chambre extrémité 1* ;

- identifiant chambre extrémité 2* ;

- type* ;

- diamètre* ;

- état de l'alvéole* ;

- occupation*.

Identifiants des chambres : pour les fourreaux servant à l'adduction d'immeubles, l'un des identifiants de chambre est remplacé par un identifiant de la propriété desservie.

Type : parmi les matériaux constitutifs des alvéoles, on peut citer le polychlorure de vinyle (PVC), le ciment, le polyéthylène haute densité (PEHCD).

Etat de l'alvéole : l'état de l'alvéole doit permettre de déterminer si celle-ci est utilisable ou non.

Occupation : l'information dont dispose l'opérateur peut être indiquée sous les formes suivantes :

- nombre de câbles présents et diamètre des câbles ;

- sous-tubage de l'alvéole et nombre de sous-tubes ;

- évaluation du taux d'occupation (0 %, 25 %, 50 %, 75 %, 100 %).

4. Site d'émission

On entend par site d'émission toute infrastructure sur laquelle est fixée une station radioélectrique utilisée pour les communications électroniques, sans restriction quant à la puissance isotrope rayonnée équivalente. Cela couvre notamment les sites faisant l'objet d'une déclaration auprès de l'Agence nationale des fréquences, conformément à l'article R. 20-4-11 (5°) du code des postes et des communications électroniques.

Attributs :

- identifiant ;

- nature ;

- hauteur du support ;

- support mutualisé ;

- systèmes ;

- position ;

- occupation*.

Identifiant : lorsque le site fait l'objet d'une déclaration auprès de l'Agence nationale des fréquences, il s'agit de l'identifiant du site utilisé dans les fichiers d'échange.

Nature : lorsque le site fait l'objet d'une déclaration auprès de l'Agence nationale des fréquences, il s'agit de la nature du support telle que définie dans la liste fournie par l'Agence nationale des fréquences.

Hauteur du support : hauteur par rapport au sol du point utile le plus élevé du support. Cette information n'est demandée que pour les sites faisant l'objet d'une déclaration auprès de l'Agence nationale des fréquences. Il s'agit du champ communiqué à l'Agence nationale des fréquences.

Support mutualisé : ce champ indique si le support est ou non mutualisé. Cette information n'est demandée que pour les sites faisant l'objet d'une déclaration auprès de l'Agence nationale des fréquences. Il s'agit du booléen support mutualisé ou site mutualisé.

Systèmes : lorsque le site fait l'objet d'une déclaration auprès de l'Agence nationale des fréquences, l'identifiant du système est choisi dans la liste fournie par l'ANFR. Il s'agit par exemple des systèmes GSM 1800, FM, RDF DVB-T, UMTS, WIMAX, WI-FI...

Position : la position est déterminée par les coordonnées géographiques du site d'émission.

Occupation : l'opérateur ou le gestionnaire d'infrastructures indique si le site est saturé ou non, c'est-à-dire s'il est encore possible d'y fixer une station radioélectrique en prenant comme référence une station de radiotéléphonie.

II. - Nœuds de réseau et équipements passifs

1. Préambule

Les réseaux sont décomposés en deux niveaux, du plus étendu au plus local :

- les " réseaux de collecte " ;

- les réseaux de desserte, ou " boucles locales ".

Les boucles locales comprennent :

- la boucle locale cuivre, en aval des nœuds de raccordement d'abonnés ;

- la boucle locale optique résidentielle, en aval des nœuds de raccordement optique ;

- la boucle locale optique professionnelle, en aval des points de présence opérateurs ;

- la boucle locale coaxiale, en aval des têtes de réseau câblé ;

- les boucles locales radioélectriques, en aval des stations de base et autres stations d'émission.

On utilise pour les boucles locales une description arborescente, uniquement basée sur les " nœuds de boucle locale " : chaque nœud fait référence au nœud de niveau immédiatement supérieur auquel il se raccroche et contient les caractéristiques propres à ce lien de rattachement. Les têtes de boucle locale (nœuds de raccordement d'abonnés, nœuds de raccordement optique...) sont considérées comme faisant partie des nœuds de boucle locale.

Les " réseaux de collecte " recouvrent tous les réseaux qui interconnectent les boucles locales, qu'il s'agisse de liens de collecte directement raccordés aux boucles locales ou de dorsales longue distance. Les points nodaux de ces réseaux, hors points d'interconnexions avec les boucles locales, constituent les nœuds et relais des réseaux de collecte.

On utilise pour les " réseaux de collecte " une représentation par liens logiques : chaque lien fait référence à deux nœuds extrémités, qui peuvent être des nœuds et relais de réseaux de collecte (au travers de " nœuds de représentation ") ou des nœuds de boucle locale.

2. Statut

Pour tous les nœuds de réseau et équipements passifs définis ci-après, l'opérateur communique les informations suivantes :

- statut de l'opérateur ;

- propriétaire du génie civil.

Le statut de l'opérateur indique notamment si celui-ci est propriétaire de l'équipement ou simplement titulaire d'un droit d'usage de longue durée. Le propriétaire du génie civil est le nom du propriétaire de l'infrastructure dans laquelle est installé le nœud du réseau ou l'équipement passif.

Ces informations ne sont pas nécessairement communiquées ponctuellement pour chaque équipement mais peuvent être communiquées de façon générique pour un sous-ensemble homogène du réseau.

3. Nœud de boucle locale

Chaque boucle locale est structurée en nœuds de réseaux. Il peut y avoir trois niveaux de nœuds : les nœuds tête de boucle locale, les nœuds intermédiaires et les nœuds de terminaison.

Les nœuds de réseau ici considérés sont :

- pour la boucle locale cuivre :

- tête de boucle : répartiteurs (NRA, NRA HD, NRA ZO) ;

- intermédiaires : sous-répartiteurs (primaires, secondaires, SRI) ;

- terminaison : points de concentration ;

- pour la boucle locale optique résidentielle :

- tête de boucle : nœuds de raccordement optique (NRO) ;

- intermédiaires : sous-répartiteurs optiques (SRO) ;

- terminaison : points de mutualisation ;

- pour la boucle locale optique professionnelle :

- tête de boucle : point de présence opérateur ;

- intermédiaires et terminaison : aucun ;

- pour la boucle locale coaxiale :

- tête de boucle : têtes de réseau câblé ;

- intermédiaires : centres de distribution (primaire, secondaire), nœuds optique-électrique ;

- terminaison : aucun ;

- pour les boucles locales radioélectriques :

- tête de boucle : stations de base et autres stations d'émission ;

- intermédiaires et terminaison : aucun.

Seuls les points de concentration de la boucle locale cuivre qui comprennent des lignes inéligibles au haut débit par DSL sont ici considérés.

a) Tronc commun.

Attributs :

- identifiant ;

- type ;

- position ;

- adresse ;

- hébergement ;

- zone de desserte ;

- nombre de lignes ;

- interconnexion ;

- identifiant du nœud " père " ;

- raccordement depuis le " père ".

Les attributs " zone de desserte " et " nombre de lignes " sont facultatifs pour les nœuds de la boucle locale optique professionnelle et des boucles locales hertziennes.

Pour les points de concentration de la boucle locale cuivre, l'opérateur fournit l'information relative aux attributs " adresse ", " hébergement ", " zone de desserte " et " nombre de lignes " lorsqu'il en dispose et peut la fournir sans effectuer un traitement excessivement complexe.

Type : on désigne par ce champ le type de nœud parmi ceux qui sont considérés dans cette section et listés ci-dessus.

Position : la position est déterminée par les coordonnées géographiques du nœud.

Hébergement : l'hébergement désigne le type d'infrastructure dans lequel le nœud est installé. Il s'agit par exemple de bâtiments, de locaux techniques, d'armoires de rue, de coffrets sur poteau, de coffrets sur façade, de pieds d'immeubles, de chambres de génie civil...

Zone de desserte : la zone de desserte désigne le secteur géographique dans lequel les lignes raccordables passent par le nœud de réseau. Cette information est transmise sous la forme d'un polygone numérique.

Pour les points de mutualisation de la boucle locale optique et les nœuds optique-électrique de la boucle locale coaxiale, la représentation sous forme de polygone peut être remplacée par une liste d'adresses correspondant aux lignes raccordables.

Nombre de lignes : ce champ désigne le nombre de lignes raccordables depuis le nœud du réseau.

Interconnexion : l'interconnexion indique si le branchement d'opérateurs tiers est possible ou non au niveau de ce nœud, le cas échéant si des opérateurs tiers y sont déjà présents.

Identifiant du nœud " père " : le nœud " père " désigne le nœud situé juste en amont dans le réseau de la boucle locale.

Cette information n'est pas demandée pour les têtes de boucle locale.

Raccordement depuis le " père " : ce champ correspond à la nature du lien utilisé entre le nœud et son père : fibre optique, câble coaxial, câble cuivre, faisceau hertzien...

L'opérateur doit au minimum indiquer si ce raccordement est en fibre optique ou non.

b) Accès à une section de boucle locale contrôlée par un opérateur tiers.

Lorsque le nœud correspond à un nœud de boucle locale propriété d'un opérateur tiers auquel l'opérateur s'interconnecte en vue d'accéder à une section de cette boucle locale (dégroupage d'un répartiteur de la boucle locale cuivre, connexion à un point de mutualisation de la boucle locale optique), l'identifiant fourni pour le nœud correspond à l'identifiant utilisé par l'opérateur tiers, si cet identifiant est connu. L'attribut interconnexion indique alors qu'il s'agit du raccordement à un nœud d'opérateur tiers.

L'opérateur qui ne contrôle pas la section aval de la boucle locale fournit l'information dont il dispose sur les attributs suivants :

- zone de desserte ;

- nombre de lignes.

Il communique en outre nécessairement l'identité de l'opérateur qui a mis en place le nœud du réseau permettant d'accéder à la partie aval de la boucle locale.

c) Compléments pour les sous-répartiteurs de la boucle locale cuivre.

Attributs complémentaires :

- atténuation ;

- lignes multiplexées.

Atténuation : l'atténuation est calculée à 300 Hz depuis le répartiteur de rattachement. Elle est fournie en décibels.

Lignes multiplexées : l'opérateur indique le nombre de lignes faisant l'objet d'un multiplexage entre le sous-répartiteur et son répartiteur de rattachement.

d) Compléments pour les points de concentration de la boucle locale cuivre qui comprennent des lignes inéligibles au haut débit DSL.

Attributs complémentaires :

-atténuation ;

- lignes inéligibles ;

- lignes multiplexées*.

Atténuation : l'atténuation est calculée à 300 Hz depuis le répartiteur de rattachement. Elle est fournie en décibels.

Lignes inéligibles : ce champ désigne le nombre de lignes inéligibles à l'internet haut débit par ADSL en raison d'une atténuation depuis le répartiteur supérieure à 78 dB.

Lignes multiplexées : l'opérateur indique le nombre de lignes faisant l'objet d'un multiplexage entre le point de concentration et son sous-répartiteur de rattachement.

e) Compléments pour les points de mutualisation de la boucle locale optique.

Le point de mutualisation désigne le lieu où l'opérateur ayant établi ou exploitant une ligne de communications électroniques à très haut débit en fibre optique dans un immeuble bâti et mettant en œuvre les obligations d'accès prévues à l'article L. 34-8-3 du code des postes et des communications électroniques donne accès aux lignes à d'autres opérateurs. Lorsque cet opérateur donne accès à son réseau en plusieurs points, le point de mutualisation est le point de livraison des accès sous forme passive, dans le respect de l'article L. 34-8-3 du code des postes et des communications électroniques.

Attributs complémentaires :

- mode de déploiement ;

- possibilité coupleur PON*.

Mode de déploiement : il s'agit du nombre de fibres prévues par logement (mono-fibre, bi-fibre, tri-fibre, quadri-fibre, etc.).

Possibilité coupleur PON : ce champ permet d'indiquer s'il est possible, sur ce point de mutualisation, d'héberger un coupleur de réseau optique passif (PON).

f) Précisions pour la boucle locale optique professionnelle.

Position/ adresse : dans le cas d'une boucle locale optique professionnelle, la localisation exacte du point de présence opérateur n'est pas demandée. L'adresse précisera uniquement la commune d'implantation. La position pourra être le centre de la commune.

Zone de desserte : la zone de desserte représente la zone raccordable : il s'agit de la zone dans laquelle une entreprise pourrait rapidement, et pour un coût raisonnable, être raccordée à la boucle optique de l'opérateur. Cette zone peut notamment être l'ensemble des points situés à moins de 150 mètres des liens optiques de l'opérateur sur lesquels il est possible de se raccorder à un point de jonction. Cette zone est définie par un polygone.

g) Compléments pour la boucle locale coaxiale.

Pour les réseaux de boucle locale coaxiale, outre l'information présentée localement pour chaque nœud, une information agrégée au niveau de sections du réseau peut également être demandée. Celle-ci concerne :

- le type de réseau câblé (réseau coaxial, 0G plan câble, 1G plan câble, HFC, FTTLA) ;

- le nombre moyen d'amplificateurs en cascade.

4. Lien du réseau de collecte

On utilise pour les " réseaux de collecte " une représentation par liens logiques, chaque lien faisant référence à deux nœuds extrémités, qui sont des nœuds de boucle locale et, si nécessaire, des nœuds de représentation des réseaux de collecte.

Attributs :

- nature ;

- identifiant extrémité A ;

- identifiant extrémité B.

Nature : la nature du lien peut être par exemple fibre optique, câble coaxial, câble cuivre, faisceau hertzien...

L'opérateur doit au minimum indiquer si ce lien contient des câbles en fibre optique ou non.

Identifiants extrémités : le tracé logique du lien est la référence à ses deux extrémités. Outre les nœuds des réseaux de boucle locale, ces extrémités peuvent être des nœuds de représentation des réseaux de collecte.

5. Nœuds de représentation des réseaux de collecte

Pour des commodités de représentation du schéma logique de son réseau de collecte, un opérateur peut être amené à introduire une extrémité autre qu'une tête de réseau de boucle locale pour définir un lien. Cette extrémité ne doit pas nécessairement correspondre à un nœud ou relais du réseau de collecte.

Attributs :

- identifiant ;

- position/ commune d'implantation.

Identifiant : l'identifiant proposé pour le nœud de représentation ne doit pas permettre d'identifier le type de nœud auquel il pourrait correspondre dans le réseau de collecte (point de présence opérateur, point de bifurcation...).

Position/ commune d'implantation : le positionnement de ces nœuds ne se fait qu'au niveau de la commune. La commune d'implantation est indiquée. La position pourra être le centre de la commune.
