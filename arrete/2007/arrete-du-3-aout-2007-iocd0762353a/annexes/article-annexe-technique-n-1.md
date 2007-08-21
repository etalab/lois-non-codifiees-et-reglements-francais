# Article Annexe technique n° 1

L'arrêté fixe des normes techniques qui portent, d'une part, sur les caméras et sur les systèmes de transmission et de stockage (articles 1er et 2), d'autre part, sur l'interopérabilité des systèmes de stockage et d'exportation des données vers les forces de police et de gendarmerie (article 3).

Afin de faciliter l'utilisation de la présente circulaire, les prescriptions de l'arrêté qu'elle commente sont reprises en italique.

1. Les caméras

" Les caméras sont réglées, équipées et connectées au système de visualisation et, le cas échéant, au système de stockage, de façon que les images restituées lors de la visualisation en temps réel ou en temps différé permettent de répondre aux finalités pour lesquelles le système de vidéosurveillance a été autorisé. "

1. 1. Les caractéristiques techniques du système de vidéosurveillance doivent permettre d'atteindre les objectifs de sécurité ayant présidé à son installation.

La première implication est que les objectifs du système et de chaque caméra, en termes de sécurité, doivent être clairement énoncés. Ces objectifs concernent le système global (taux d'indisponibilité accepté, caractéristiques du système de stockage...) ainsi que les caméras proprement dites, dont les rôles doivent être définis.A titre d'exemple, tel groupe de caméras pourra avoir comme rôle principal de permettre la levée de doute avant une ouverture de porte, alors que tel autre groupe de caméras aura comme objectif principal de permettre l'analyse de l'image en temps réel comme, par exemple, la reconnaissance d'individus ayant accédé à une zone donnée.

1. 2. La qualité des images.

La seconde implication, fondamentale, est que les caractéristiques techniques du système doivent être cohérentes avec les objectifs énoncés. Ce point est essentiel car, si la diversité des situations interdit de définir de manière absolue ce que doivent être les caractéristiques techniques d'un système pour obtenir un certain résultat, il est toujours possible en revanche de vérifier la cohérence d'un système avec les objectifs qui lui sont assignés.L'arrêté précise que cette vérification ne doit pas se faire exclusivement sur les différents éléments du système (qualité des caméras, qualité des liaisons de données, qualité de la compression des images...) mais sur la qualité des images restituées.

Cette mise en cohérence impose à l'opérateur d'adapter les éléments déficients ou mal dimensionnés du système lorsque la qualité des images restituées est incompatible avec les objectifs de celui-ci.

Le contrôle de cette cohérence lors de l'examen de la demande d'autorisation préalable à l'installation, donc " sur dossier ", peut s'avérer difficile. Une annexe technique fournit néanmoins quelques repères dont les services des préfectures pourront s'inspirer lors de l'examen des dossiers.

Il convient toutefois d'attirer l'attention sur le fait que cette première prescription présente un intérêt certain dans l'hypothèse d'un contrôle a posteriori du système, lors de la demande de renouvellement de l'autorisation par exemple.

" Les caméras présentent les caractéristiques techniques adaptées aux conditions d'illumination du lieu vidéosurveillé ".

Il s'agit de vérifier simplement que l'opérateur a pris en compte les spécificités liées à l'illumination des scènes à vidéosurveiller lors du choix des caméras. En effet, s'il s'agit de pouvoir enregistrer des images de qualité en vision nocturne, alors il conviendra soit d'utiliser des caméras à haute sensibilité soit de prévoir un éclairage d'appoint, infrarouge par exemple. Ces éléments doivent aller de pair avec les conditions particulières d'éclairage des scènes filmées, qui devront être également précisées (un éclairage intense peut en effet, en intérieur notamment, autoriser l'usage d'une caméra moins sensible).

2. La transmission des images

" Les réseaux sur lesquels transitent les flux vidéo offrent une bande passante compatible avec les débits nécessaires à la transmission d'images de qualité suffisante pour répondre aux finalités pour lesquelles le système de vidéosurveillance a été autorisé. "

Les images issues des caméras, pour être transmises sur les réseaux, doivent être codées et généralement compressées pour pouvoir être communiquées en temps réel au travers des artères de transmission. Le débit maximum de ces voies de transmission, appelé bande passante, conditionne donc directement la qualité des images réceptionnées. Ainsi, une bande passante insuffisante entraînera automatiquement une perte de qualité (compression des images trop importante induisant une perte préjudiciable d'information) ou de performance (diminution du nombre d'images par seconde ou choix de ne pas transmettre tous les flux).

La diversité des cas d'utilisation (image fixe ou avec beaucoup de mouvement par exemple) et des dispositifs techniques (compression MPEG 2, MPEG 4, JPEG, JPEG 2000...) ne permet pas de définir à l'avance la bande passante minimum nécessaire à la transmission numérique d'une image de qualité, cette qualité dépendant également de l'objectif de sécurité fixé. Il est rappelé pour mémoire, que le poids moyen d'une image d'excellente qualité est de 45 Ko. En revanche, le tableau ci-dessous donne un aperçu de l'ordre de grandeur de la bande passante utilisée pour transmettre des images avec certaines caractéristiques pour les différentes classes de compression de données.

TYPE DE MÉCANISME DE COMPRESSION

DÉBIT THÉORIQUE MOYEN pour disposer d'images au format 4 CIF à 12 images par seconde

Tableau non reproduit ; consulter le fac-similé

Ainsi, si un opérateur déclare faire transiter 8 flux simultanés d'images, au format 4 CIF à 12 images par seconde comprimées au format MPEG 2 (2 Mbits x 8 = 16 Mbits de débit théorique nécessaire à la transmission de ces flux), sur un système disposant d'une bande passante de 4Mbits, il conviendra de s'interroger sur la pertinence de ce choix.

" Les réseaux sur lesquels transitent les flux vidéo prennent en compte la sécurité de ces derniers, garantissant leur disponibilité, leur confidentialité et leur intégrité. "

Les données restituées par les systèmes de vidéosurveillance doivent présenter trois types de caractéristiques essentielles :

-elles doivent être conformes aux images originelles. Ces dernières ne doivent donc pas avoir été corrompues ou modifiées durant leur transfert. Le système de transmission doit offrir une garantie d'intégrité des données communiquées ;

-elles doivent être accessibles en cas de sollicitation. Pour cela, il faut en premier lieu que le système de transmission soit robuste aux dysfonctionnements comme aux éventuelles agressions externes. Il doit offrir une garantie de disponibilité des données communiquées ;

-elles ne doivent être accessibles qu'aux personnes habilitées à en disposer. Cela implique que des dispositifs spécifiques doivent être mis en oeuvre pour empêcher l'interception et la lecture des données transmises. Le système de transmission doit donc offrir une garantie de confidentialité des données échangées, le plus souvent par le biais de fonctions de chiffrement adaptées.

Il ne s'agit pas ici de se livrer à une expertise de sécurité exhaustive garantissant ces trois critères, ni même de solliciter l'opérateur pour un certificat formel de sécurité. En revanche, il convient de s'assurer que ces critères ont été pris en compte et que les solutions mises en oeuvre adressent ces trois sujets.

Le cas des transmissions numériques sans fil (technologies dites Wi-Fi ou Wi-Max par exemple) méritent assurément une attention particulière. En effet, l'interception des flux est par nature aisée ainsi que, dans une moindre mesure, le " déni de service ". Il convient donc que, d'une part, l'opérateur garantisse la confidentialité des données par l'utilisation d'un chiffrement adapté et fiable et que, d'autre part, il limite l'usage de ces technologies aux segments de réseau terminaux ou impropres aux technologies filaires.

3. Le stockage

" Le stockage des flux vidéo est réalisé sur support numérique pour les systèmes de vidéosurveillance comportant huit caméras ou plus. Ce stockage peut également être réalisé sur un autre type de support. Le stockage des flux vidéo est réalisé sur support analogique ou numérique pour les systèmes de vidéosurveillance comportant moins de huit caméras. "

Lorsqu'une installation de vidéosurveillance devient importante, il n'est pas concevable, dans un objectif de qualité de service, d'utiliser un stockage de type analogique. Le stockage numérique est donc impératif. Il convient de noter que cette contrainte ne porte que sur le module d'enregistrement des images, ce qui implique notamment que rien n'interdit d'utiliser des caméras analogiques dont les flux seront numérisés par la suite. Il est toutefois précisé que le stockage peut également être réalisé sur un autre type de support afin de permettre aux opérateurs de conserver leur système d'enregistrement analogique (type cassettes VHS), en plus du système d'enregistrement numérique qu'ils seront tenus de mettre en place.

Pour limiter le coût d'installation de petits systèmes de vidéosurveillance, il est possible d'utiliser un support de stockage analogique apportant une plus grande facilité d'installation et d'utilisation. Les systèmes visés ici, qui comportent sept caméras ou moins, doivent être compris comme ceux destinés à sécuriser une entité géographique autonome.A titre d'exemple, une entreprise qui dépose une demande d'autorisation pour des systèmes de vidéosurveillance dans chacune de ses agences (donc indépendants et autonomes) peut concevoir ces systèmes comme autonomes pour chacune d'elles. Dans ce cas, toutes les agences de sept caméras ou moins sont autorisées à conserver un système de stockage de type analogique. Néanmoins, il faut bien préciser que ces systèmes ne sont considérés comme autonomes que si le stockage et / ou la visualisation s'effectue (nt) dans chacune des agences. Si les vidéos des agences sont rapatriées sur un ou plusieurs sites communs, alors les systèmes de chaque agence ne peuvent plus être considérés comme indépendants.

" Tout flux vidéo enregistré numériquement est stocké avec des informations permettant de déterminer à tout moment de la séquence vidéo sa date, son heure et l'emplacement de la caméra. "

Dans l'objectif de pouvoir utiliser les images vidéo stockées dans des procédures judiciaires, il est nécessaire de pouvoir certifier les informations spatiales et temporelles associées aux images.L'article 2, deuxième alinéa, de l'arrêté du 26 septembre 2006 ne vise explicitement que la capacité du système d'enregistrement à associer aux images ces trois données. Son esprit est toutefois de permettre à un service enquêteur d'utiliser efficacement les données numériques transmises, ce qui a une double implication :

-les paramètres de date et de localisation doivent être accessibles à l'enquêteur avec le système de visualisation dont il dispose ;

-les paramètres doivent être exacts.

Il conviendra donc de s'assurer, dans la mesure du possible, que ces deux contraintes ont été prises en compte.

Il existe une méthode simple qui consiste à marquer ces informations directement sur l'image vidéo. Néanmoins, cette méthode a le désavantage de masquer des parties de l'image. Une autre méthode consiste à associer les informations avec le flux vidéo, puis de créer une liaison logicielle entre les images et le fichier d'information associé. Dans ce cas particulier, les lecteurs fournis aux services d'enquête devront disposer d'une capacité spécifique pour réassocier les données et les images lors de leur exploitation.

L'opérateur du système de vidéosurveillance devra par ailleurs préciser comment il s'assure de la fiabilité du référentiel temporel qui sera associé aux images.

" Pour les systèmes à enregistrement analogique des flux vidéo, un dispositif permet de déterminer à tout moment la date, l'heure et l'emplacement de la caméra correspondant aux images enregistrées. "

Le besoin des forces de police est identique quelle que soit la nature du système, seul le mécanisme de stockage des informations associées aux images sera différent. Dans le cas d'enregistrement analogique (du type cassettes VHS), les informations doivent exister mais leur format (fichier papier ou numérique) n'est pas précisé. Il conviendra néanmoins de s'assurer que les enquêteurs pourront disposer de ces informations lors de l'analyse des images. Les données associées aux supports analogiques doivent donc pouvoir leur être communiquées avec les cassettes vidéo.

" L'enregistrement numérique garantit l'intégrité des flux vidéo et des données associées relatives à la date, à l'heure et à l'emplacement de la caméra. ".

Les moyens à mettre en oeuvre pour garantir l'intégrité des flux vidéo et des données associées relatives à la date, à l'heure et à l'emplacement de la caméra ne sont pas spécifiés. En particulier, il n'est pas exigé ici que les systèmes intègrent des dispositifs de marquage électronique des images (parfois appelé watermarking ou filigranage), même si ces dispositifs sont les bienvenus et doivent être encouragés. En effet, un système numérique robuste quant aux traces enregistrées (toute intervention de nature à modifier les données est immanquablement enregistrée) et à l'environnement d'exploitation (qui garantit notamment l'intégrité du système de traces) est susceptible d'atteindre les objectifs d'intégrité.

" Les flux vidéo stockés issus des caméras qui, compte tenu de leur positionnement et de leur orientation, fonctionnent principalement en plan étroit, à l'exclusion de celles de régulation du trafic routier, ont un format d'image supérieur ou égal à 704 x 576 pixels. Ce format pourra être inférieur si le système permet l'extraction de vignettes de visage d'une résolution minimum de 90 x 60 pixels. "

L'objet de l'article 2, cinquième alinéa, est de favoriser l'existence d'images d'une précision satisfaisante pour le travail des enquêteurs. Il pose donc le principe d'un niveau de qualité minimum des images stockées lorsqu'elles sont issues de caméras fonctionnant en plan étroit.

L'équilibre recherché ici consiste à garantir un bon niveau de qualité des images seulement lorsque c'est nécessaire pour les forces de police et de gendarmerie, sans faire peser des contraintes techniques trop importantes sur les parties du dispositif qui concernent moins directement le travail d'investigation.

Pour cela, on distingue deux grands types de caméras de vidéosurveillance, celles dont la fonction principale est d'analyser les informations sur les individus ou les objets présents dans le champ des caméras (qui sont dites fonctionner en plan étroit) et celles dont la fonction principale est de fournir une vue globale de la situation (qui sont dites fonctionner en plan large).

Cette classification appelle deux remarques et mérite d'être illustrée par quelques exemples.

Tout d'abord, il est entendu que les caméras qui constituent un dispositif de vidéosurveillance ont le plus souvent des missions multiples. Ceci est d'autant plus vrai que certaines caméras sont dotées de fonctions de zoom et d'orientation rapide qui leur permettent d'offrir un plan global et de passer l'instant suivant en plan rapproché. Néanmoins, il reste qu'à chaque caméra est le plus souvent assigné un objectif principal d'exploitation : levée de doute, gestion d'une file d'attente, surveillance d'un objectif sensible, contrôle des flux...

Il est nécessaire que ces objectifs principaux soient précisés pour chaque caméra dans les dossiers transmis par les opérateurs. Le plus souvent ils doivent permettre de statuer sur la classification des caméras à plan large ou à plan étroit.

Ensuite, il est légitime de s'interroger sur la corrélation éventuelle entre les caractéristiques techniques en termes de focale ou de zoom des caméras et leur usage en plan large ou plan étroit (telles que ces notions ont été définies ci-dessus). Compte tenu de la diversité des usages de la vidéosurveillance, ce lien ne semble pas être pertinent. En effet, une caméra destinée à garantir la sécurité d'un distributeur automatique de billets ou à sécuriser les entrées-sorties dans un bus peut, du fait de la faible distance à la cible, fonctionner avec une ouverture angulaire importante, alors qu'au sens de l'arrêté du 26 septembre 2006 il s'agit bien, compte tenu de la précision attendue de l'image, d'un fonctionnement en plan étroit. De la même manière, certaines caméras destinées à sécuriser des voies ferrées peuvent fonctionner avec une petite ouverture angulaire mais en plan large au sens de l'arrêté, si elles sont destinées à la régulation du trafic ferroviaire.

La résolution de 704 x 576 correspond au format dit 4 CIF, normalisé dans le domaine de la vidéo, compatible avec les performances de la majorité des caméras installées et constituant la norme haute en matière de définition d'image en attendant la généralisation des caméras dites à haute définition. La définition visée dans cet article concerne les images stockées sur le système d'enregistrement. Ceci implique que toute la chaîne vidéo doit afficher des caractéristiques compatibles avec ces formats d'enregistrement : la résolution des capteurs (caractéristiques techniques des caméras), le format d'image en sortie de caméra, le taux de compression des images lors du transfert et du stockage. Une autre conséquence est que les espaces de stockage doivent être compatibles avec les caractéristiques globales du système. Il est donc important que les spécifications techniques (définition, taux de compression, nombre d'images par seconde, durée de conservation des données, nombre de flux stockés) du système soient précisées ainsi que le calcul menant au dimensionnement des espaces de stockage.

Dans certains cas, il n'est pas nécessaire de disposer d'une image de 704 x 576 pixels pour offrir une résolution satisfaisante des sujets filmés. Les opérateurs ont donc toute latitude pour retenir un format inférieur pour peu que celui-ci propose, dans la zone nominale de prise de vue, une résolution permettant l'identification d'un visage. En particulier, des caméras numériques au format VGA (640 x 480 pixels) qui permettraient l'extraction sur les vidéos enregistrées de vignettes de visage de 90 x 60 pixels conviennent.

Il est certain que la diversité des situations occasionnera inévitablement des cas litigieux ou ambigus pour lesquels la proposition de classification plan large / plan étroit du soumissionnaire pourra apparaître discutable. Pour déterminer de façon pratique les caractéristiques minimales des images stockées, le tableau d'exemples proposé en annexe I doit permettre le plus souvent d'assimiler ces situations à un cas d'usage approchant déjà traité.

" Les autres flux vidéo stockés ont un format d'image supérieur ou égal à 352 x 288 pixels ".

Tous les autres flux vidéo issus des systèmes de vidéosurveillance visés par la loi du 21 janvier 1995, modifiée par la loi du 23 janvier 2006, doivent au minimum être stockés avec une résolution de 352 x 288 pixels, aussi appelé format CIF.C'est notamment le cas des images issues d'un dispositif de régulation du trafic routier.

" Une fréquence minimale de douze images par seconde est requise pour l'enregistrement des flux vidéo issus de caméras installées pour une des finalités mentionnées au II de l'article 10 de la loi du 21 janvier 1995 susvisée, à l'exclusion de celles de régulation du trafic routier, et qui, compte tenu de leur positionnement et de leur orientation, fonctionnent principalement en plan étroit et filment principalement des flux d'individus en déplacement rapide. "

Le nombre d'images par seconde constitue également un paramètre important lorsqu'il s'agit de chercher des éléments précis dans une scène vidéo en mouvement. Il convient pourtant de moduler les exigences en fonction des besoins opérationnels véritables pour ne pas surdimensionner le système de vidéosurveillance inutilement.C'est pourquoi l'exigence de disposer de 12 images enregistrées par seconde ne s'applique qu'aux caméras fonctionnant principalement en plan étroit (cf. article 2, alinéa 5) et parmi celles-ci exclusivement à celles destinées à surveiller des flux de personnes en " déplacement rapide ".

Cette notion fait explicitement référence à des situations où les individus filmés sont, sauf circonstances particulières, en train de marcher sans rencontrer d'obstacle lorsqu'ils traversent la zone de prise de vue. Il est question en particulier de déplacement rapide pour les caméras destinées à filmer un espace de transit dans les lieux publics (couloir de métro, hall d'aéroport, trottoir urbain...). En revanche ne sont pas considérées comme des déplacements rapides les images d'individus en train de franchir une porte ou un tourniquet de métro, ou stationnant dans un hall destiné à l'attente ou au recueil de bagages.

Les cas de figure les plus typiques ou susceptibles de poser problèmes sont évoqués en annexe 2.

" Pour l'enregistrement des autres flux vidéo, une fréquence minimale de six images par seconde est requise. "

Toutes les autres images visées par la loi du 21 janvier 1995 doivent au minimum être enregistrées à une cadence réelle de 6 images par seconde à partir d'une caméra dont bien entendu la fréquence d'acquisition des images sera d'au minimum 6 images par seconde. Ainsi, il ne serait donc être question de reconstruire artificiellement un flux à 6 images par seconde à partir par exemple d'une séquence initiale à 3 images par seconde. Il en est de même pour un enregistrement à 12 images par seconde.

" Le système de stockage utilisé est associé à un journal qui conserve la trace de l'ensemble des actions effectuées sur les flux vidéo. "

La traçabilité des actions effectuées sur le système est primordiale pour vérifier qu'aucun abus et qu'aucune action de malveillance n'ont été commis. Dans le cas des systèmes d'enregistrement analogique ou des systèmes de vidéosurveillance numériques de moins de huit caméras, un journal qui conserve la trace de l'ensemble des actions effectuées sur les flux (export, modification, suppression...) peut être tenu à la main.

" Pour les systèmes numériques, ce journal est généré automatiquement sous forme électronique. "

Pour simplifier l'opération de journalisation, qui peut être fastidieuse pour de gros systèmes, il faut que, pour les systèmes numériques, cette opération soit automatisée. Il conviendra donc de s'assurer que le système proposé intègre cette fonction et que l'opérateur prévoie dans son plan d'exploitation de la mettre en oeuvre.

4. Les contraintes d'interopérabilité

L'arrêté du 26 septembre 2006 a pour objectif que les techniques de la vidéosurveillance puissent mettre en oeuvre de façon concrète les dispositions que la loi du 21 janvier 1995 modifiée a édictées.

Les dispositions de l'article 3 de l'arrêté précité ont pour but de faciliter concrètement l'exploitation des systèmes par les services de police et de gendarmerie.

" Les flux vidéo sont exportés sans dégradation de la qualité. "

La transmission des films vidéo aux forces de police et de gendarmerie nécessite une opération dite " d'exportation ". Il est nécessaire que la qualité des images exportées soit maximale, ce qui implique que le système doit être en mesure d'exporter ses données sans perte de qualité.

Si, lors de l'opération d'exportation, il s'avère nécessaire de modifier le format ou le type de compression des flux vidéo, il conviendra alors de s'assurer que la compression des vidéos exportées ne dégrade pas leur qualité.

Il est donc important de connaître la méthode d'exportation des flux vidéo et, dans le cas où il ne s'agit pas d'une simple copie des données, les caractéristiques de la compression utilisée pour le stockage et l'exportation.

" Pour les systèmes de vidéosurveillance utilisant la technologie analogique, un dispositif détermine la liste des flux exportés, indiquant la date et l'heure des images filmées, leur durée, l'identifiant des caméras concernées, la date et l'heure de l'exportation, l'identité de la personne ayant réalisé l'exportation. "

Il est important de conserver une traçabilité des exportations pour assurer qu'aucun abus ne soit commis. La difficulté de cette mesure pour un système de vidéosurveillance analogique, et dans une moindre mesure pour les systèmes numériques de moins huit caméras, est parfois le manque d'automatisation du système. Il est alors nécessaire d'intégrer dans la procédure d'exportation de flux vidéo la constitution manuelle d'un journal des différentes opérations effectuées sur le système. Cette action de constitution d'un journal doit en particulier permettre de pouvoir identifier la ou les personnes qui ont exporté les flux vidéo.

" Pour les systèmes de vidéosurveillance utilisant la technologie numérique, un journal électronique des exportations, comportant les informations citées à l'alinéa précédent, est généré automatiquement. "

De même que pour les systèmes analogiques, la traçabilité des exportations est, pour les systèmes numériques, primordiale.L'avantage d'un système numérique est la possibilité d'automatiser des actions. Ainsi, pour assurer l'exactitude des informations contenues dans la liste des flux exportés, il suffit de créer un " journal " électronique constitué automatiquement par le système.

" Le système d'enregistrement reste en fonctionnement lors de ces opérations d'exportation. "

L'exportation de données ne doit en aucun cas diminuer les capacités d'un système de vidéosurveillance. En effet, il serait fortement dommageable que, lors de l'exportation d'images vidéo, un événement grave se produise et qu'il soit impossible d'enregistrer les flux vidéo y afférents. Le fait que le système d'enregistrement reste en fonctionnement lors des opérations d'exportation vise en particulier à interdire l'extraction des unités de stockage du système durant les phases d'investigation si cette action interdit la poursuite du fonctionnement normal du système. Il est donc important de vérifier que la procédure d'exportation soit conforme à cette exigence. Une méthode simple consiste à prévoir des supports de stockage supplémentaires afin de remplacer ceux qui seraient temporairement extraits du système.

" Le support physique d'exportation est un support numérique non réinscriptible et à accès direct, compatible avec le volume de données à exporter. Dans le cas de volumes importants de données à exporter, des disques durs utilisant une connectique standard pourront être utilisés. Pour les systèmes numériques de vidéosurveillance, un logiciel permettant l'exploitation des images est fourni sur support numérique, disjoint du support des données. "

Le système de stockage des enregistrements vidéo doit être doté de la capacité à exporter des films et des photos vers un support non réinscriptible, qui, en l'état actuel, sera le plus souvent du type graveur de CD ou de DVD. Tous les systèmes doivent donc disposer de cette fonctionnalité. Ceci implique notamment que les clés USB (qui constituent un support réinscriptible) ne peuvent être le seul support d'exportation sur un tel système.

Le support doit de plus être à accès direct, c'est-à-dire que les informations doivent être accessibles sans avoir à parcourir séquentiellement l'ensemble du support. En particulier, les cassettes DAT ne peuvent constituer un support d'exportation valable.

Toutefois, il est parfois nécessaire d'exporter une quantité importante de données. Dans ce cas exclusivement, il est autorisé d'utiliser des disques durs, qui permettent une plus grande capacité de stockage. Cette possibilité vient s'ajouter à la capacité d'export sur des supports non réinscriptibles, qui constituent dans tous les cas le moyen par défaut de transmission des données vers les forces de sécurité.

" Le logiciel permet :

" 1° La lecture des flux vidéo sans dégradation de la qualité de l'image ;

" 2° La lecture des flux vidéo en accéléré, en arrière, au ralenti ;

" 3° La lecture image par image des flux vidéo, l'arrêt sur une image, la sauvegarde d'une image et d'une séquence, dans un format standard sans perte d'information ;

" 4° L'affichage sur l'écran de l'identifiant de la caméra, de la date et de l'heure de l'enregistrement ;

" 5° La recherche par caméra, date et heure. "

Les flux vidéo sont exportés pour être traités par les services de police ou de gendarmerie. Les caractéristiques mentionnées doivent donc être intégrées dans le logiciel de lecture, fourni sur un support numérique séparé distinct de celui des images, par l'opérateur aux services enquêteurs en même temps que les images.
