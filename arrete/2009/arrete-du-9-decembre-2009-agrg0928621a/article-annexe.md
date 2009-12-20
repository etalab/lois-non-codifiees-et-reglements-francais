# Article Annexe

**CAHIER DES CHARGES-BASE DE DONNÉES NATIONALE D'ABATTAGE DES BOVINS**

Préambule

En application de la loi n° 2008-582 du 20 juin 2008 et du décret n° 2009-605 du 29 mai 2009 pris pour application de l'article L. 212-12-1 du code rural, le présent cahier des charges précise les conditions selon lesquelles le ministère en charge de l'agriculture confie la gestion, le recueil, la collecte des données d'identification et de mouvements des bovins destinés à être abattus et leur traitement à une personne agréée dénommée ci-après gestionnaire de la base de données nationale d'abattage des bovins.

Le gestionnaire de la base de données nationale d'abattage des bovins déploie un réseau permanent d'assistance aux utilisateurs de ladite base sur l'ensemble du territoire national (métropole et départements d'outre-mer).

L'association NORMABEV désignée " gestionnaire de la base de données nationale d'abattage des bovins " à l'issue de l'appel à candidatures met matériellement en œuvre les missions qui lui sont confiées dans les conditions définies dans le présent cahier des charges.

Les missions confiées au gestionnaire de la base de données nationale d'abattage des bovins portent sur :

1. La gestion de la base de données nationale d'abattage des bovins ;

2. La mise en place et la gestion des outils permettant aux personnes autorisées de saisir, mettre à jour et / ou consulter les données ;

3. La collecte des données réglementaires des mouvements de bovins destinés à être abattus et leur transfert en base de données nationale d'identification (BDNI).

Pour remplir ces missions, le gestionnaire de la base de données nationale d'abattage des bovins dispose de :

Une base de données, dont la taille est fonction :

― des volumes de données à traiter :

230 exploitations d'abattage ;

250 interlocuteurs ;

5 000 000 mouvements d'abattage par an ;

― du nombre d'utilisateurs potentiels :

230 exploitations d'abattage ;

1 organisme (BDNI).

Le gestionnaire de la base de données d'abattage des bovins transmet quotidiennement à la base de données nationale d'identification (BDNI) et en flux continu les notifications d'abattage.

Un service de mise à jour de la base de données nationale d'abattage des bovins à partir des fournitures quotidiennes de données de la BDNI.

Un service d'accès en temps réel aux données de cette base.

Un service de téléchargement des données de cette base sous forme de fichiers.

Un service de sauvegarde et d'archivage des échanges.

Un service d'inscription et de gestion des mots de passe.

Un service d'assistance aux utilisateurs par des structures compétentes.

Un service de gestion des licences d'utilisation des données réglementaires contenues dans la base de données nationale d'abattage des bovins.

Les fonctionnalités minimales disponibles sont :

― la notification des mouvements d'abattage de bovins par transmission de fichiers ;

― la correction des mouvements d'abattage par les personnes autorisées ;

― la consultation des données enregistrées dans la base de données nationale d'abattage des bovins en fonction des droits accordés à chaque utilisateur ;

― les changements de coordonnées personnelles recueillies par le gestionnaire ;

― la consultation des informations personnelles.

Le gestionnaire de la base de données nationale d'abattage des bovins assure un service continu et met en œuvre toutes les sécurités adéquates à la protection du système. Par ailleurs, le système mis en place permet un suivi des opérations effectuées, une mise à jour des données et la constitution de requêtes automatisées de consultation.

Le système informatique est suffisamment souple et adaptable pour suivre les évolutions réglementaires et notamment de nouvelles fonctionnalités ou pour répondre à des demandes ponctuelles d'extraction.

1. Gestion de la base de données nationale d'abattage des bovins

La base de données nationale d'abattage des bovins contient des données relatives aux détenteurs, aux exploitations, aux bovins qui y sont abattus et à leurs mouvements.

Ces données sont la propriété du ministère en charge de l'agriculture.

Les données ci-dessous sont contenues dans la base de données nationale d'abattage des bovins :

1-A. Données relatives au détenteur des animaux :

― date et heure de mise à jour ;

― code pays détenteur ;

― numéro détenteur (= N° attribué par l'EdE) ;

― raison sociale ou situation civile ;

― dénomination du détenteur ;

― adresses du détenteur ;

― code localisation du détenteur (= code postal) ;

― commune du détenteur ;

― numéro de SIREN du détenteur ou NUMAGRIN ;

― code pays de résidence du détenteur.

1-B. Données relatives à l'exploitation :

― date et heure de mise à jour ;

― code pays d'exploitation ;

― numéro d'exploitation (= N° EdE) ;

― numéro d'agrément sanitaire ;

― date de début d'activité de l'exploitation ;

― date de fin d'activité de l'exploitation ;

― type d'exploitation ;

― raison sociale ou situation civile ;

― dénomination de l'exploitation ;

― adresses de l'exploitation ;

― code localisation de l'exploitation (= code postal) ;

― commune de l'exploitation ;

― code pays du détenteur ;

― numéro du détenteur actif ;

― numéro de SIRET de l'exploitation ou NUMAGRIT ;

― coordonnées géographiques de l'exploitation.

1-C. Données relatives à l'abattage des bovins :

1-C. 1. Données concernant les animaux :

― le nombre d'animaux abattus ;

― le nombre de morts durant le transport, en bouverie, au déchargement, euthanasie et saisie totale avant la pesée.

1-C. 2. Données concernant la provenance :

― le type de lieu de provenance (élevage) ;

― l'identifiant du lieu du chargement : numéro d'exploitation d'élevage.

1-C. 3. Données concernant l'abattage des animaux :

― la date d'entrée en bouverie (facultatif) ;

― la date d'abattage ;

― numéro de tuerie (facultatif) ;

― poids de carcasse (facultatif).

Le gestionnaire de la base de données nationale d'abattage des bovins collecte, traite et / ou met à jour les données listées au point 1C. Le ministère en charge de l'agriculture transmet au gestionnaire de la base de données nationale d'abattage des bovins les données listées aux points 1A et 1B.

Pour l'ensemble des anomalies listées ci-dessous, qui peuvent être relevées et / ou générées lors de la notification des abattages par les abattoirs, le gestionnaire de la base de données nationale d'abattage des bovins :

― reçoit les anomalies " abattage " transmises par la BDNI ;

― les adresse à l'exploitant d'abattoir ;

― transfère à la BDNI les corrections reçues de l'abattoir.

Liste des anomalies :

― une notification d'abattage avec même animal, même abattoir, même date d'abattage, existe déjà ;

― l'abattoir a déjà notifié un abattage pour cet animal avec un écart de moins de 7 (*) jours entre les 2 dates d'abattage ;

― une notification identique existe déjà ;

― l'abattoir n'est pas connu en BDNI ;

― l'animal n'existe pas ou est mort-né et l'exploitation de provenance est inconnue ;

― l'animal n'existe pas ou est mort-né et l'exploitation de provenance n'est pas une exploitation d'élevage ;

― l'animal n'existe pas ou est mort-né ;

― un autre abattoir a déjà notifié un abattage pour cet animal avec un écart de moins de 7 (*) jours entre les 2 dates d'abattage ;

― l'exploitation de provenance est inconnue ;

― l'exploitation de provenance n'est pas une exploitation d'élevage ;

― l'exploitation de provenance ne correspond pas à l'exploitation de dernière détention de l'animal. Elle est égale à son exploitation de naissance ;

― l'exploitation de provenance est une exploitation d'élevage où l'animal a été détenu mais elle ne correspond pas à l'exploitation de dernière détention ;

― l'exploitation de provenance est une exploitation d'élevage où l'animal n'a jamais été détenu. Elle ne correspond pas à l'exploitation de dernière détention ;

― la date d'abattage de l'animal est antérieure à sa date de naissance ;

― la date d'abattage de l'animal se situe entre deux périodes de présence de l'animal dans des exploitations d'élevage ;

― la date d'abattage de l'animal se situe dans une période où il est présent dans une exploitation d'élevage ;

― la date d'abattage de l'animal est antérieure de plus de 7 (*) jours à sa date de sortie de la dernière exploitation d'élevage où il a été détenu ;

― il y a un écart de plus de 30 jours entre la date d'abattage ou la date d'entrée en bouverie de l'animal et sa dernière sortie d'une exploitation d'élevage.

Le gestionnaire de la base de données nationale d'abattage des bovins doit présenter à tout moment les données enregistrées dans la base de données nationale d'abattage des bovins, sous réserve que les données aient été effectivement portées à sa connaissance.

Le gestionnaire de la base de données nationale d'abattage des bovins doit faire fonctionner et maintenir la base de données nationale d'abattage des bovins sur une période de dix ans, sous réserve des dispositions de l'article R. 212-14-1 du code rural.

Le gestionnaire de la base de données nationale d'abattage des bovins doit disposer des moyens appropriés permettant de vérifier le respect de l'obligation des délais de notification, notamment par l'enregistrement et la conservation des dates de saisie et de transmission des données à ladite base.

En cas d'urgence sanitaire, le gestionnaire de la base de données nationale d'abattage des bovins met en œuvre tout moyen matériel et humain, en accord avec son fonctionnement interne, pour répondre aux demandes éventuelles du ministère en charge de l'agriculture.

2. Mise en place et gestion des outils permettant aux personnes autorisées de saisir, mettre à jour et / ou consulter les données

Le gestionnaire de la base de données nationale d'abattage des bovins met en place et administre un site internet unique commun à tous les exploitants d'abattoir et à tous les responsables de l'identification bovine (BDNI).

Un portail permet aux internautes autorisés d'accéder à toutes les fonctionnalités et données utiles concernant l'identification et les abattages de bovins, dans la limite de leurs droits.

Les conditions générales d'utilisation de la base de données nationale d'abattage des bovins sont consultables en ligne sur le site internet de la base de données par toutes les personnes autorisées.

Le gestionnaire de la base de données nationale d'abattage des bovins accorde les identifiants et les codes d'accès aux personnes autorisées, contrôle et limite les accès aux fonctionnalités auxquels ils ont droit.

Les personnes autorisées ne peuvent être que celles prévues par le décret n° 2009-605 du 29 mai 2009, et outre celles ayant un accès direct précisées à l'article 7 de l'arrêté ministériel, ont un accès aux données, en particulier :

-les comités régionaux interprofessionnels qui transmettent les données au dernier détenteur du bovin abattu ;

-le dernier détenteur du bovin abattu ;

-l'institut de l'élevage ;

-l'Institut national de recherche agronomique (INRA).

Le gestionnaire de la base de données nationale d'abattage des bovins met en place un dispositif sécurisé permettant l'envoi des mots de passe aux personnes autorisées.

Le gestionnaire de la base de données nationale d'abattage des bovins met en place les moyens informatiques suffisants et sécurisés à la saisie et à la mise à jour des données réglementaires par les personnes autorisées.

Des moyens informatiques de connexion et de transfert des données peuvent être proposés aux personnes autorisées pour contrôler et, le cas échéant, corriger la saisie des données réglementaires. Dans ce cas, le gestionnaire de la base de données nationale d'abattage des bovins garantit un système de transmission des données sécurisé.

Le gestionnaire de la base de données nationale d'abattage des bovins met en place des protections particulières, d'une part, afin d'éviter une interrogation abusive ou toute intrusion dans la base de données nationale d'abattage des bovins et, d'autre part, pour signaler au ministère en charge de l'agriculture tout usage de ce droit d'accès pour des finalités autres que celles prévues dans le présent cahier des charges.

Le gestionnaire de la base de données nationale d'abattage des bovins répertorie et conserve pendant six mois les traces des interrogations et des utilisations de ladite base.

Le gestionnaire de la base de données nationale d'abattage des bovins conserve pendant six mois l'historique des comptes de chaque utilisateur de ladite base ainsi que l'historique des droits accordés à chacun.

Dès qu'il en a connaissance, le gestionnaire de la base de données nationale d'abattage des bovins invalide les accès attribués à des personnes ayant perdu leur qualité d'ayant droit, de professionnel ou de toute autre catégorie.

Le gestionnaire de la base de données nationale d'abattage des bovins assure à chaque détenteur l'accès à ses propres données sur la base de son numéro d'exploitation ou de son numéro d'agrément.

A l'exception du ministère en charge de l'agriculture, toute demande de requêtes contenant des données non anonymisées doit faire l'objet d'une demande dans le respect des conditions définies par la loi CNIL.

A la demande du ministère en charge de l'agriculture en cas de crise sanitaire, le gestionnaire de la base de données nationale d'abattage des bovins répond dans un délai ne dépassant pas trois jours ouvrés à toute requête relative aux données enregistrées dans ladite base.

3. Transfert des données réglementaires vers la base de données nationale d'identification des abattages de bovins

Le gestionnaire de la base de données nationale d'abattage des bovins respecte les exigences techniques de modalités de transfert des données de la BDNI vers ladite base, décrites dans un cahier des charges techniques spécifiques.

Le gestionnaire de la base de données nationale d'abattage des bovins transmet à la BDNI, les données réglementaires collectées, selon des modalités de transfert décrites dans un cahier des charges techniques spécifiques.

4. Suivi de la base de données d'abattage des bovins

La gestion de la base de données nationale d'abattage des bovins est placée sous le contrôle d'une commission, chargée de vérifier le respect du présent cahier des charges, d'émettre un avis sur les comptes d'exploitation présentés par le gestionnaire de la base.

Toute demande de requête anonymisée, à l'exception de celle du ministère en charge de l'agriculture en cas de crise sanitaire, peut donner lieu à la perception d'une somme fixée par le ministère en charge de l'agriculture sur proposition du gestionnaire de la base de données nationale d'abattage des bovins dans le cadre d'une licence d'utilisation approuvée par le ministère en charge de l'agriculture.

Le gestionnaire de la base de données nationale d'abattage des bovins garantit que les données nominatives contenues dans la base de données nationale d'abattage des bovins ne sont utilisées qu'à des fins de gestion de ladite base ; les données nominatives (données listées au point 1A du premier paragraphe) ne pouvant pas être utilisées dans le cadre d'une autre activité exercée par le gestionnaire de ladite base.

5. Planning

Le calendrier de la mise en place de la base de données d'abattage des bovins est le suivant :

JA : publication de l'arrêté de désignation du gestionnaire de la base de données nationale d'abattage des bovins par le ministère en charge de l'agriculture et de l'arrêté fixant les modalités de gestion et de fonctionnement de ladite base.

JA : la base de données nationale d'abattage des bovins est ouverte dans trois départements pilotes.

JA : déploiement des moyens humains pour la gestion de la base de données nationale d'abattage des bovins au niveau national (métropole et départements d'outre-mer).

JA : extension de la base de données nationale d'abattage des bovins au niveau national (métropole et départements d'outre-mer).

JA : consultation des données de la base de données nationale d'abattage des bovins par chaque détenteur.

JA : gestion des mesures correctives des anomalies.

JA : possibilité de faire des requêtes à partir de la base de données nationale d'abattage des bovins.

<font color="#808080" size="1">
<em>(*) Le délai est susceptible d'évoluer au cours de la période d'agrément.</em>
</font>
