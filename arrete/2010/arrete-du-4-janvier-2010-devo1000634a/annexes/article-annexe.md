# Article Annexe

FICHIER DE LIAISON RECETTES SUR RÔLES

FICHIER ROLMRE

I. - Caractéristiques propres différenciant

"ROLMRE" de "INDIGO"

Ce fichier de liaison est destiné à la communication des recettes massives ou répétitives mises en recouvrement par les ordonnateurs, par voie de rôles collectifs et non de titres individuels.

Il présente trois caractéristiques principales qui en font, pour ces opérations, un instrument de communication mieux adapté que ne le serait le fichier "INDIGO" :

11. Il permet l'utilisation d'un identifiant des débiteurs autre que le numéro de titre éventuellement complété par un numéro d'ordre, obligatoire dans le cas de "INDIGO".

Cette souplesse est particulièrement utile dans le cas des recettes dont la liquidation est effectuée chez l'ordonnateur au moyen de chaînes spécialisées, indépendantes de l'application financière et comptable au sein de laquelle les mises recouvrement ne sont alors intégrées que postérieurement, en un ou plusieurs titres collectifs.

12. Il permet de répondre aux besoins spécifiques résultant, quant aux données à communiquer, des particularités propres aux redevances d'eau et d'assainissement = recettes à ventiler entre deux budgets, éventuellement assorties de TVA et susceptibles d'être majorées au taux de 25 %.

Cette orientation ne fait pas obstacle à l'utilisation du fichier ROLMRE pour l'ensemble des produits massifs des collectivités ou des organismes qui dépendent d'elles, que ces produits soient ou non assortis de TVA : cantines scolaires, redevances d'enlèvement des ordures ménagères, droits de voirie, régies municipales d'électricité, télédistribution, etc.

13. Il permet la mise en œuvre de traitements adaptés aux besoins du recouvrement de masse :

- recours possible aux prélèvements automatiques sur comptes bancaires ou postaux ;

- regroupement (en interrogation) des impayés d'un même débiteur lorsqu'un identifiant permanent débiteur est susceptible d'être fourni par l'ordonnateur ;

- suivi particulier des frais de poursuites.

II. - Les aménagements apportés au fichier

ROLMRE, dont la version initiale, définie en 1990, doit à la fois, prendre en compte les évolutions obligées (an 2000, euro, impact de la loi sur l'eau et les milieux aquatiques de 2006) et adopter une normalisation des informations transmises (adresse, zones montant).

21. L'an 2000.

L'année est décrite sur 4 caractères dans les deux zones dates :

- ROLEX = exercice de rattachement budgétaire ;

- ROLDAT = date d'émission.

L'allongement de la zone ROLEX est sans conséquence sur les modalités de calcul des clés de contrôle 1 et 2 : seuls les deux derniers chiffres de ROLEX y sont utilisés comme précédemment.

22. Passage à l'euro.

Un code monnaie, zone ROLMONNAIE en position 465, est intégré à ROLMRE.

23. Normalisation de l'adresse.

Afin de répondre aux normes définies par La Poste, six zones de 32 caractères sont désormais disponibles pour transmettre les informations suivantes :

- deux premières zones = le nom et tout élément d'identification du débiteur ;

- troisième zone = mentions complémentaires de distribution (bâtiment, résidence...) ;

- quatrième zone = l'adresse rue du débiteur ;

- cinquième zone = le nom d'un lieudit ou d'un hameau ;

- sixième zone = le code postal et la localité de destination.

La taille de 32 caractères est également adoptée pour les deux zones, ROLORU et ROLOVI, qui décrivent l'objet de la recette.

24. Normalisation des zones montants.

Les six zones transmises se composent désormais de 12 chiffres dont 2 décimales.

25. Transmission du numéro de dette : cas particulier de l'application EAU (Eau et assainissement : réseau BULL).

Le numéro de dette utilisé dans l'application EAU se compose de 15 chiffres ; or la zone ROLDET prévue dans le fichier ROLMRE ne contient que 13 caractères. Dans le cas, rare, où le numéro à transmettre comporte 14 ou 15 chiffres significatifs, il est nécessaire de le scinder en deux dans ROLMRE :

- les deux premiers chiffres, à gauche, dans une zone nouvelle ROLDEB (positions 467 et 468) créée à cet usage ;

- les 13 suivants en zone ROLDET.

Si la zone ROLDEB est ainsi utilisée, le calcul de la clé de contrôle 2 est modifié et porte sur l'ensemble (2 derniers chiffres de ROLEX + ROLPER + ROLDEB + ROLDET).

26. Création d'un code version.

Afin de déterminer la version du fichier ROLMRE transmise lors d'un envoi, un code est placé en 500e caractère. Il est systématiquement égal à 2 lorsque ROLMRE correspond à la présente version.

27. Impact de la loi sur l'eau et les milieux aquatiques n° 2006-1772 du 30 décembre 2006 (LEMA).

Il est créé un code en position 499, qui permet de distinguer les enregistrements véhiculant des redevances d'eau et/ou assainissement des enregistrements véhiculant des redevances pour pollution d'origine domestique et/ou pour modernisation des réseaux de collecte.

La transmission des redevances eau/assainissement et pollution/modernisation doit être simultanée et le numéro de dette (zone ROLDET) doit être identique pour un même débiteur sur les 2 enregistrements.

III. - Dessin des enregistrements

30. Généralités.

- Le fichier ROLMRE a été étudié pour pouvoir servir d'instrument de liaison unique au niveau national, ce qui explique certaines redondances d'informations dues à la diversité des matériels et logiciels équipant les départements informatiques du Trésor.

- Organisation séquentielle.

- Enregistrements de longueur fixe (500 caractères).

- Aucun critère de tri particulier n'est exigé des ordonnateurs (tri par numéro croissant d'identifiant effectué par les services du Trésor préalablement à l'exploitation des fichiers).

- La périodicité des transmissions, variant essentiellement avec le type de recette, sera déterminée cas par cas, en accord entre l'ordonnateur et le centre informatique du Trésor.

31. Structure.

310. Elle est uniforme quel que soit le type de comptabilité auquel se rattachent les recettes.

Chacun des enregistrements figurant sur le fichier correspond à une dette. La structure est uniforme quel que soit le type de recette, seul variant le nombre des zones utilisées, les zones sans objet devant être mises à espaces ou à zéros selon leur nature.

Afin de répondre aux spécificités des deux applications informatiques du Trésor (EAU et EAS) traitant le recouvrement des recettes sur rôles, certaines zones de ROLMRE ont été redéfinies.

Les remarques suivantes précisent l'utilisation de l'ensemble des zones de ROLMRE.

311. Code mouvement (zone ROLMVT, caractère 1).

Actuellement constante de valeur 1 (création).

312. Référence de la dette.

3120. Code collectivité-établissement (zone ROLCOL, caractères 2 et 3).

Mêmes caractéristiques que pour les fichiers MAIREC, MAIDEP et BUDMRE.

3121. Nature du rôle (zone ROLNAT, caractères 4 et 5).

Zone numérique destinée à identifier la nature de la recette. Ce numéro est attribué après accord entre l'ordonnateur et le département informatique régional du Trésor.

3122. Exercice (zone ROLEX, caractères 6 à 9).

Zone destinée à recevoir l'exercice de rattachement budgétaire.

3123. Code période (zone ROLPER, caractère 10).

Zone numérique destinée à recevoir un numéro de rôle pour écarter, à l'intérieur d'un exercice et d'un même type de rôle, tout risque de synonymie dans les références d'une dette.

Si son utilisation s'avère inutile, la zone peut recevoir une valeur constante.

3124. Numéro de dette (zone ROLDET, caractères 11 à 23).

Numéro attribué par l'ordonnateur pour identifier une dette. Sa structure est libre à condition de ne pas laisser apparaître de synonymes pour une même collectivité (ROLCOL), un même type de recette (ROLREC), un même exercice (ROLEX) et un même code période (ROLPER) : il peut comprendre, outre un numéro séquentiel, un numéro de quartier, de tournée...

Cependant, un numéro comportant un minimum de caractères serait de nature à alléger la charge de saisie du poste comptable.

3125. Clé de contrôle (zone ROLCLE1, caractère 24).

Clé numérique calculée selon le modulo 11 (voir annexe ).

Cette clé est calculée à partir des zones (ROLCOL + ROLNAT + 2 derniers chiffres de ROLEX + ROLPER + ROLDET).

3126. Zone ROLNUL (caractère 25).

Valeur actuellement égale à zéro.

3127. Clé de contrôle 2 (zone ROLCLE2, caractère 26).

Clé alpha calculée selon le modulo 23 (voir annexe ).

Elle est calculée sur (2 derniers chiffres de ROLEX + ROLPER + 00 + ROLDET).

Dans le cas où la zone ROLDEB est utilisée pour transmettre le début du numéro de dette, la clé est alors calculée sur (2 derniers chiffres de ROLEX + ROLPER +ROLDEB + ROLDET).

3128. Code recette (zone ROLREC, caractères 27 et 28).

Code alphabétique à l'exclusion de FF destiné à identifier la nature de la recette ; attribué après accord de l'ordonnateur et du département informatique du Trésor.

Il est préférable d'utiliser un code significatif (ex. : EA pour une dette d'eau et assainissement).

313. Date d'émission (zone ROLDAT, caractères 29 à 36).

Date de prise en charge sous la forme AAAAMMJJ à partir de laquelle seront calculés les délais pour l'édition des documents concernant la phase contentieuse du recouvrement.

314. Numéro de rôle (zone ROLROL, caractères 37 et 38).

Destiné à la numérotation séquentielle des rôles au fur et à mesure de leur émission.

315. Montant eau HTVA (zone ROLEAU, caractères 39 à 50)

Cette zone reçoit le montant EAU hors taxe en centimes dans le cas de recettes d'eau et d'assainissement ou le montant hors taxe en centimes de la redevance pour pollution d'origine domestique. Dans le cas d'autres recettes n'obéissant à aucune règle particulière quant au recouvrement ou à la majoration, cette zone recevra le montant budgétaire à recouvrer.

316. Montant assainissement HTVA (zone ROLASS, caractères 51 à 62).

Cette zone reçoit éventuellement le montant en centimes de la dette correspondant à la redevance d'assainissement ou à la redevance pour modernisation des réseaux de collecte susceptible de faire l'objet d'une majoration en cas de non-paiement dans le délai prescrit.

317. Montant TVA sur eau et montant TVA sur assainissement (zones ROLTVE, caractères 63 à 74, et ROLTVA, caractères 75 à 86).

Destinées à recevoir éventuellement le montant en centimes de la TVA due sur chaque fraction de la dette. Sinon les zones sont à zéro.

Il va de soi que ces zones n'ont à être utilisées que pour les services (ou les opérations) pour lesquels la TVA est versée au Trésor (ou récupérée), la recette budgétaire (zone ROLEAU et ROLASS) étant alors hors TVA. Dans le cas d'une recette budgétaire TTC, le montant TTC doit figurer dans les zones ROLEAU et ROLASS, les zones destinées à la TVA sont alors à zéro.

Ces zones ne doivent pas être servies pour les enregistrements portant les montants relatifs aux redevances pour pollution d'origine domestique et/ou pour modernisation des réseaux de collecte (code enregistrement en position 499 = 2) : dans ce cas la TVA éventuelle est cumulée avec la TVA de la dette principale (code enregistrement = 1).

318. Montant total (zone ROLTOT, caractères 87 à 98).

Somme en centimes, nécessairement positive, correspondant au total des montants indiqués dans les zones ROLEAU, ROLASS, ROLTVE et ROLTVA.

319. Assainissement non majorable (zone ROLNMAJ, caractères 99 à 110).

Cette zone est destinée à recevoir la fraction de la dette assainissement non susceptible de majoration (par exemple travaux effectués pour le compte de l'usager). Ce montant figure donc pour mémoire et n'est pas additionné dans la zone ROLTOT.

Cette zone n'a à être renseignée que dans le cas de redevances d'assainissement susceptibles d'être majorées. Sinon, la mettre à zéro.

NB : Toutes les zones Montants utilisées sont obligatoirement positives. Les zones non utilisées sont à zéro.

3191. - Nom et adresse du débiteur.

Six zones alphanumériques de 32 caractères. Les informations sont cadrées à gauche et éventuellement complétées par des espaces. Les zones non utilisées sont à espaces.

ROLNOM (caractères 111 à 142) contient la partie significative du nom du débiteur :

[nom suivi du prénom du débiteur séparé d'un espace. Le nom ne doit pas être précédé de l'état civil (M., Mr, Mme, Mlle)].

ROLCNM (caractères 143 à 174) : suite, si besoin est, des éléments significatifs de l'identification tels que raison sociale ou dénomination sociale, titre et qualité du destinataire, indication d'étage, d'appartement, de porte, numéro de boîte aux lettres...

ROLDIS (caractères 175 à 206) : mentions complémentaires de distribution (bâtiment, escalier, nom de résidence...).

ROLADR (caractères 207 à 238) : adresse, rue (numéro, type et nom de voie).

ROLCVI (caractères 239 à 270) : complément de la commune, nom d'un lieudit ou d'un hameau.

ROLCP (5 caractères en positions, 271 à 275) : code postal.

ROLLOC (27 caractères en positions, 276 à 302) : localité de destination.

3192. Objet de la recette (zones ROLORU, caractères 303 à 334, et ROLOVI, caractères 335 à 366).

Cette zone peut recevoir l'adresse du point de livraison (recette eau & assainissement) ou toute autre indication au choix de l'ordonnateur destinée à préciser au redevable l'objet de sa dette sur les avis de relance édités par les services du Trésor.

Cadrer à gauche et compléter par des espaces.

3193. Code prélèvement (zone ROLPRE, caractères 367).

Cette zone a comme valeur 5 si le débiteur a demandé à se libérer de sa dette par prélèvement automatique sur compte bancaire ou postal et la valeur 2 pour les non-prélevés.

3194. Références bancaires (4 zones).

ROLRET (5 caractères en positions 368 à 372) : code établissement bancaire.

ROLRGU (5 caractères en positions 373 à 377) : code guichet bancaire.

ROLRCO (11 caractères en positions 378 à 388) : numéro de compte bancaire.

ROLRCL (2 caractères en positions 389 et 390) : clé RIB.

3195. Titulaire du compte (zone ROLTIT, caractères 391 à 414).

Cadrer cette zone à gauche et éventuellement compléter par des zéros.

3196. Numéro de compte client (zone ROLCLI, caractères 415 à 434).

Cette zone d'utilisation facultative est destinée à recevoir un identifiant fixe et unique par débiteur ou, à défaut, un numéro de point de branchement, un numéro de compteur, etc.

Cette zone permettra ultérieurement le regroupement (en interrogation) des différentes dettes d'un même débiteur, quelle que soit leur nature.

Cette zone doit être cadrée à gauche et complétée éventuellement à droite par des espaces.

Dans l'hypothèse où il n'existe pas d'identifiant fixe, celle-ci doit être mise à espaces.

A noter que le fichier retour (TRESOR ordonnateur) FLUOR clients n'a de sens que si cette zone est servie dans le fichier aller ROLMRE.

3197. Imputation budgétaire (zones ROLSCH, caractères 435 à 444, et ROLART, caractères 445 à 464).

Ces zones facultatives seront servies en fonction de l'instruction comptable appliquée pour le type de recette (zones non utilisées actuellement).

3198. Code monnaie (zone ROLMONNAIE, caractères 465).

Zone prenant la valeur :

E depuis le 1er janvier 2002.

3199. Zone ROLHOM (caractères 466) : zone laissée à espace.

3200. Zone ROLDEB (numérique, caractères 467 et 468).

Cette zone est utilisée lorsque le numéro de dette, sur 15 chiffres, comporte plus de 13 chiffres significatifs. Dans ce cas, les deux premiers chiffres, à gauche, sont transférés dans ROLDEB, le reste l'étant dans ROLDET.

Dans tous les autres cas, la zone est laissée à zéro.

3201. FILLER (caractères 469 à 498).

3202. ROLTPR (caractère 499) : cette zone permet de déterminer le type de produit et peut prendre les valeurs suivantes :

1 = eau/assainissement.

2 = redevances LEMA.

0 = autres ou différent de 1 et 2.

3203. ROLVER (position 500) indique la version de ROLMRE utilisée.

Ce code sera systématiquement égal à 2 dans la nouvelle version décrite par cette note.
