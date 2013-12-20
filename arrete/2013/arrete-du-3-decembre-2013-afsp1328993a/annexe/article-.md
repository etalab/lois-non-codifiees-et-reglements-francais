# Article 

FORMAT CSV

Généralités

<table>
<tbody>
<tr>
<td width="144">
<p align="center">FORMAT</p>
</td>
<td width="367">
<p align="center">DESCRIPTION</p>
</td>
<td width="143">
<p align="center">EXEMPLE DE VALEUR</p>
</td>
</tr>
<tr>
<td width="144">
<p>TEXTE</p>
</td>
<td width="367">
<p>Alphanumérique en majuscules sans accent et de longueur au plus égale à 256 caractères</p>
</td>
<td width="143">
<p align="center">MEDECIN</p>
</td>
</tr>
<tr>
<td width="144">
<p>IDENTIFIANT</p>
</td>
<td width="367">
<p>[0-9][A-Z] - Caractères tiret et underscore autorisés - Longueur au plus égale à 128 caractères</p>
</td>
<td width="143">
<p align="center">1234-67</p>
</td>
</tr>
<tr>
<td width="144">
<p>MONTANT</p>
</td>
<td width="367">
<p>Montant : entier arrondi à l'euro supérieur au plus égal à 1 000 000 (à valider)</p>
</td>
<td width="143">
<p align="center">159</p>
</td>
</tr>
<tr>
<td width="144">
<p>CODEPOSTAL</p>
</td>
<td width="367">
<p>Code postal : alphanumérique sur 10 caractères</p>
</td>
<td width="143">
<p align="center">75008</p>
</td>
</tr>
<tr>
<td width="144">
<p>DATE</p>
</td>
<td width="367">
<p>Date : JJ/MM/AAAA sur 10 caractères</p>
</td>
<td width="143">
<p align="center">05/09/2013</p>
</td>
</tr>
<tr>
<td width="144">
<p>LISTE</p>
</td>
<td width="367">
<p>Valeur parmi une liste de valeurs possibles - Entre crochets</p>
</td>
<td width="143">
<p align="center">[RPPS]</p>
</td>
</tr>
</tbody>
</table>

.

<table>
<tbody>
<tr>
<td width="668">
<p align="center">RÈGLES DE GESTION LIÉES AU FICHIER CSV</p>
</td>
</tr>
<tr>
<td width="668">
<p>Format : UTF-8</p>
</td>
</tr>
<tr>
<td width="668">
<p>Séparateur : Pipe (c'est-à-dire |)</p>
</td>
</tr>
<tr>
<td width="668">
<p>En-tête de colonne sur la première ligne : oui (obligatoire)</p>
</td>
</tr>
<tr>
<td width="668">
<p>Nom du fichier : identifiant#AAAAMMJJ#HHmmss#declaration.csv</p>
</td>
</tr>
<tr>
<td width="668">
<p>Avec identifiant = identifiant de connexion du compte déclarant obtenu lors de l'inscription au site unique</p>
</td>
</tr>
<tr>
<td width="668">
<p>Exemple : 12345678#20130905#205612#declaration.csv</p>
</td>
</tr>
</tbody>
</table>

.

<table>
<tbody>
<tr>
<td width="668">
<p align="center">RÈGLES DE GESTION LIÉES AU FORMAT</p>
</td>
</tr>
<tr>
<td width="668">
<p>Un champ obligatoire non rempli génère une erreur (donc la ligne de déclaration n'est pas importée)</p>
</td>
</tr>
<tr>
<td width="668">
<p>Un champ de type LISTE dont la valeur n'appartient pas à la liste des valeurs possibles génère une erreur</p>
</td>
</tr>
<tr>
<td width="668">
<p>Un champ dont la valeur ne correspond pas à son format génère une erreur</p>
</td>
</tr>
</tbody>
</table>

.

<table>
<tbody>
<tr>
<td width="668">
<p align="center">AUTRES RÈGLES DE GESTION</p>
</td>
</tr>
<tr>
<td width="668">
<p>Une valeur non renseignée ne correspond à aucun caractère (et non un caractère espace par exemple)</p>
</td>
</tr>
<tr>
<td width="668">
<p>Exemple en 3e position : [A]|21/09/2013||Manifestation</p>
</td>
</tr>
<tr>
<td width="668">
<p>Aucune valeur ne peut contenir le caractère pipe (|)</p>
</td>
</tr>
</tbody>
</table>

Déclaration

<table>
<tbody>
<tr>
<td>
<p align="center">NOM <br/>du champ</p>
</td>
<td>
<p align="center">OBLIGATOIRE</p>
</td>
<td>
<p align="center">UNICITÉ</p>
</td>
<td>
<p align="center">DESCRIPTIF<br/>du champ</p>
</td>
<td>
<p align="center">FORMAT</p>
</td>
<td>
<p align="center">LISTE <br/>de valeurs/<br/>commentaire</p>
</td>
<td>
<p align="center">RÈGLE<br/>de gestion<br/>alerte </p>
</td>
<td>
<p align="center">RÈGLE <br/>de gestion<br/>erreur </p>
</td>
</tr>
<tr>
<td width="119">
<p>ENTREPRISE_IDENTIFIANT</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td rowspan="2" width="69">
<p align="center">Le couple (ENTREPRISE</p>
<p align="center">IDENTIFIANT, LIGNE_IDENTIFIANT) est unique</p>
</td>
<td width="76">
<p>Identifiant unique de l'entreprise ayant signé cette convention ou versé cet avantage</p>
</td>
<td width="66">
<p align="center">IDENTIFIANT</p>
</td>
<td width="93">
<p>Cette valeur permet d'attacher cette ligne de déclaration à l'entreprise (mandant) concernée si une entreprise (mandataire) transmet cette ligne de déclaration. Cette colonne permet de gérer le cas d'une entreprise qui déclare pour d'autres entreprises lui ayant donné mandat. Sinon l'entreprise déclarante indique son propre identifiant récupéré lors de son inscription sur le site unique.</p>
</td>
<td width="58"/>
<td width="71">
<p>Si la valeur ENTREPRISE_IDENTIFIANt#LIGNE</p>
<p>_IDENTIFIANT existe déjà dans le système et que la valeur LIGNE_ACTION est égale à [C] ;<br/>Si la valeur ENTREPRISE_IDENTIFIANt#LIGNE_</p>
<p>IDENTIFIANT n'existe pas dans le système et que la valeur LIGNE_ACTION est égale à [M] ou [V] ;<br/>Si la valeur ENTREPRISE_IDENTIFIANT n'existe pas dans le système ;<br/>Si la valeur ENTREPRISE_IDENTIFIANT n'est pas un compte (ou un sous-compte) géré par le compte de l'utilisateur qui importe le fichier ou appelle le service web (gestion des habilitations).</p>
</td>
</tr>
<tr>
<td width="119">
<p>LIGNE_IDENTIFIANT</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="76">
<p>Identifiant unique de la ligne de déclaration (convention ou avantage) dans le système de l'entreprise déclarante</p>
</td>
<td width="66">
<p align="center">IDENTIFIANT</p>
</td>
<td width="93">
<p>Cette valeur joue le rôle de clé pour identifier de manière unique cette ligne de déclaration (avantage ou convention). Elle est fournie en entrée par l'entreprise pour pouvoir par exemple procéder à une correction ultérieure.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>LIGNE_ACTION</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Code action</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[C] pour Création ;<br/>[M] pour Modification ;<br/>[S] pour Suppression ;<br/>[V] pour Validation (cas d'un retour suite à alerte).<br/>Important : lorsque le champ LIGNE_ACTION est égal à [V], aucun contrôle de type ALERTE n'est réalisé puisque l'entreprise valide les données de cette ligne de déclaration. En revanche les contrôles de type ERREUR sont toujours exécutés.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>LIGNE_DEMANDE_</p>
<p>RECTIFICATION</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Ligne corrige une demande de rectification d'un bénéficiaire.</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[O] Oui ;<br/>[N] Non.<br/>Si [O], suppression du marqueur de demande de rectification du bénéficiaire sur le site grand public.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_CATEGORIE</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Catégorie du bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[PRS] Les professionnels de santé relevant de la quatrième partie du présent code ;<br/>[APS] Les associations de professionnels de santé ;<br/>[ETU] Les étudiants se destinant aux professions relevant de la quatrième partie du présent code ainsi que les associations et groupements les représentant ;<br/>[AUS] Les associations d'usagers du système de santé ;<br/>[ETA] Les établissements de santé relevant de la sixième partie du présent code ;<br/>[FON] Les fondations, les sociétés savantes et les sociétés ou organismes de conseil intervenant dans le secteur des produits ou prestations mentionnés au premier alinéa ;<br/>[PRE] Les entreprises éditrices de presse, les éditeurs de services de radio ou de télévision et les éditeurs de services de communication au public en ligne ;<br/>[LOG] Les éditeurs de logiciels d'aide à la prescription et à la délivrance ;<br/>[PMO] Les personnes morales assurant la formation initiale des professionnels de santé mentionnés au 1° ou participant à cette formation.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_NOM</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [ETU] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Nom du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] et [ETU].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_PRENOM</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [ETU] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Prénom du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] et [ETU].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_QUALITE</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Qualité/profession du bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[10] Médecin ;<br/>[40] Chirurgien-dentiste ;<br/>[50] Sage-femme ;<br/>[21] Pharmacien ;<br/>[01] Préparateur en pharmacie et préparateur en pharmacie hospitalière ;<br/>[60] Infirmier ;<br/>[70] Masseur-kinésithérapeute ;<br/>[80] Pédicure-podologue ;<br/>[94] Ergothérapeute ;<br/>[96] Psychomotricien ;<br/>[91] Orthophoniste ;<br/>[92] Orthoptiste ;<br/>[98] Manipulateur d'électroradiologie médicale ;<br/>[86] Technicien de laboratoire médical ;<br/>[05] Audioprothésiste ;<br/>[28] Opticien-lunetier ;<br/>[82] Prothésiste et orthésiste pour l'appareillage des personnes handicapées ;<br/>[95] Diététicien ;<br/>[02] Aide-soignant ;<br/>[03] Auxiliaire de puériculture ;<br/>[04] Ambulancier.</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ADRESSE1</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Adresse du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93">
<p>Adresse professionnelle si la valeur du champ BENEF_CATEGORIE est égale à [PRS] ;<br/>Adresse siège social ou équivalent si la valeur du champ BENEF_CATEGORIE est égale à [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ADRESSE2</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Complément 1 de l'adresse du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ADRESSE3</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Complément 2 de l'adresse du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ADRESSE4</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Complément 3 de l'adresse du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_CODEPOSTAL</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Code postal du bénéficiaire</p>
</td>
<td width="66">
<p align="center">CODEPOSTAL</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_VILLE</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Ville du bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_PAYS</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Pays du bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>Norme ISO 3166-1 alpha-2 (entre crochets).<br/>Exemple : [FR] pour France.</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS] ou [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_TITRE</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Titre du bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[PR] Professeur ;<br/>[MG] Médecin général ;<br/>[PG] Pharmacien général ;<br/>[PC] Pharmacien-chef ;<br/>[MC] Médecin-chef ;<br/>[DR] Docteur ;<br/>[AUTRE] Autre.</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td rowspan="5" valign="top" width="119">
<p>BENEF_SPECIALITE</p>
</td>
<td rowspan="5" valign="top" width="68">
<p align="center">Non</p>
</td>
<td rowspan="5" valign="top" width="69">
<p align="center">Non</p>
</td>
<td rowspan="5" valign="top" width="76">
<p align="center">Spécialité (ou discipline) du bénéficiaire</p>
</td>
<td rowspan="5" valign="top" width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[SCD01] Orthopédie dento-faciale ;<br/>[SCD02] Chirurgie orale ;<br/>[SCD03] Médecine bucco-dentaire ;<br/>[SM01] Anatomie et cytologie pathologiques ;<br/>[SM02] Anesthésie-réanimation ;<br/>[SM03] Biologie médicale ;<br/>[SM04] Cardiologie et maladies vasculaires ;<br/>[SM05] Chirurgie générale ;<br/>[SM06] Chirurgie maxillo-faciale ;<br/>[SM07] Chirurgie maxillo-faciale et stomatologie ;<br/>[SM08] Chirurgie orthopédique et traumatologie ;<br/>[SM09] Chirurgie infantile ;</p>
</td>
<td rowspan="5" valign="top" width="58">
<p align="center">Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS].</p>
</td>
<td rowspan="5" width="71"/>
</tr>
<tr>
<td width="93">
<p>[SM10] Chirurgie plastique reconstructrice et esthétique ;<br/>[SM11] Chirurgie thoracique et cardio-vasculaire ;<br/>[SM12] Chirurgie urologique ;<br/>[SM13] Chirurgie vasculaire ;<br/>[SM14] Chirurgie viscérale et digestive ;<br/>[SM15] Dermatologie et vénéréologie ;<br/>[SM16] Endocrinologie et métabolisme ;<br/>[SM17] Génétique médicale ;<br/>[SM18] Gériatrie ;<br/>[SM19] Gynécologie médicale ;</p>
</td>
</tr>
<tr>
<td width="93">
<p>[SM20] Gynécologie-obstétrique ;<br/>[SM21] Hématologie ;<br/>[SM22] Hématologie (option maladie du sang) ;<br/>[SM23] Hématologie (option onco-hématologie) ;<br/>[SM24] Gastro-entérologie et hépatologie ;<br/>[SM25] Médecine du travail ;<br/>[SM26] Qualifié en médecine générale ;<br/>[SM27] Médecine interne ;<br/>[SM28] Médecine nucléaire ;<br/>[SM29] Médecine physique et réadaptation ;<br/>[SM30] Néphrologie ;<br/>[SM31] Neuro-chirurgie ;<br/>[SM32] Neurologie ;<br/>[SM33] Neuro-psychiatrie ;<br/>[SM34] ORL et chirurgie cervico-faciale ;<br/>[SM35] Oncologie (option onco-hématologie) ;</p>
</td>
</tr>
<tr>
<td width="93">
<p>[SM36] Oncologie (option médicale) ;<br/>[SM37] Oncologie (option radiothérapie) ;<br/>[SM38] Ophtalmologie ;<br/>[SM39] Oto-rhino-laryngologie ;<br/>[SM40] Pédiatrie ;<br/>[SM41] Pneumologie ;<br/>[SM42] Psychiatrie ;<br/>[SM43] Psychiatrie (option enfant et adolescent) ;<br/>[SM44] Radiodiagnostic ;<br/>[SM45] Radiothérapie ;<br/>[SM46] Réanimation médicale ;<br/>[SM47] Recherche médicale ;<br/>[SM48] Rhumatologie ;<br/>[SM49] Santé publique et médecine sociale ;<br/>[SM50] Stomatologie ;<br/>[SM51] Gynéco-obstétrique et gynécologie médicale option ;</p>
</td>
</tr>
<tr>
<td width="93">
<p>[SM52] Gynéco-obstétrique et gynécologie médicale option ;<br/>[SM53] Spécialiste en médecine générale ;<br/>[SM54] Médecine générale ;<br/>[SM55] Radiodiagnostic et radio-thérapie ;<br/>[SM99] ORL et ophtalmologie ;<br/>[SP01] Radiopharmacie ;<br/>[SP02] Hygiène ;<br/>[SP03] Pharmacovigilance ;<br/>[SP04] Hémovigilance ;<br/>[AUTRE] Autre.</p>
</td>
</tr>
<tr>
<td width="119">
<p>BENEF_QUALIFICATION</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Qualification du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93">
<p>Champ volontairement libre</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [PRS].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_IDENTIFIANT_TYPE</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Type d'identifiant utilisé pour identifier le bénéficiaire</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[RPPS] pour l'identifiant personnel du bénéficiaire dans le répertoire partagé des professionnels de santé ;<br/>[ORDRE] pour le numéro d'inscription à l'ordre ;<br/>[AUTRE] pour les autres cas.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_IDENTIFIANT_VALEUR</p>
</td>
<td width="68">
<p align="center">Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Valeur de l'identifiant du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93">
<p>Si le champ BENEF_IDENTIFIANT_TYPE égal à [RPPS], identifiant personnel du bénéficiaire dans le répertoire partagé des professionnels de santé ;<br/>Si le champ BENEF_IDENTIFIANT_TYPE égal à [ORDRE], numéro d'inscription à l'ordre ;<br/>[SO] si le champ BENEF_IDENTIFIANT_TYPE égal à [AUTRE] et la valeur est non renseignée ;<br/>Valeur libre si le champ BENEF_IDENTIFIANT_TYPE égal à [AUTRE] et la valeur est renseignée.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ETABLISSEMENT</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [ETU] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Nom de l'établissement d'enseignement</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [ETU].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ETABLISSEMENT_</p>
<p>CODEPOSTAL</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [ETU] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Code postal de l'établissement d'enseignement</p>
</td>
<td width="66">
<p align="center">CODEPOSTAL</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [ETU].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_ETABLISSEMENT_VILLE</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [ETU] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Ville de l'établissement d'enseignement</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [ETU].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_DENOMINATIONSOCIALE</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Dénomination sociale du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>BENEF_OBJETSOCIAL</p>
</td>
<td width="68">
<p>Oui si le champ BENEF_CATEGORIE a la valeur [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO] ;<br/>Non sinon.</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Objet social du bénéficiaire</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ BENEF_CATEGORIE est différente de [APS] ou [AUS] ou [ETA] ou [FON] ou [PRE] ou [LOG] ou [PMO].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>LIGNE_TYPE</p>
</td>
<td width="68">
<p>Oui</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Avantage ou convention</p>
</td>
<td width="66">
<p align="center">LISTE</p>
</td>
<td width="93">
<p>[A] pour Avantage ;<br/>[C] pour Convention.</p>
</td>
<td width="58"/>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_DATE_SIGNATURE</p>
</td>
<td width="68">
<p>Oui si le champ LIGNE_TYPE est égal à [C] ;<br/>Non sinon (dans ce cas les lignes sont ignorées).</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Date de signature de la convention</p>
</td>
<td width="66">
<p align="center">DATE</p>
</td>
<td width="93">
<p>Format JJ/MM/AAAA</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_OBJET</p>
</td>
<td width="68"/>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Objet de la convention</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_DATE_DEBUT</p>
</td>
<td width="68"/>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Date de début de couverture de la convention</p>
</td>
<td width="66">
<p align="center">DATE</p>
</td>
<td width="93">
<p>Format JJ/MM/AAAA</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_DATE_FIN</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Date de fin de couverture de la convention</p>
</td>
<td width="66">
<p align="center">DATE</p>
</td>
<td width="93">
<p>Format JJ/MM/AAAA</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_EVENEMENT_DATE</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Date de l'événement lié à la convention</p>
</td>
<td width="66">
<p align="center">DATE</p>
</td>
<td width="93">
<p>Format JJ/MM/AAAA<br/>A compléter si la convention concerne une manifestation (remplace le dépôt du programme sous forme de PDF)</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_EVENEMENT_NOM</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Nom de l'événement lié à la convention</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93">
<p>A compléter si la convention concerne une manifestation (remplace le dépôt du programme sous forme de PDF)</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>CONV_EVENEMENT_LIEU</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Lieu de l'événement lié à la convention</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93">
<p>A compléter si la convention concerne une manifestation (remplace le dépôt du programme sous forme de PDF)</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [C].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>AVANT_DATE</p>
</td>
<td width="68">
<p>Oui si le champ LIGNE_TYPE est égal à [A] ;<br/>Non sinon (dans ce cas les lignes sont ignorées).</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Date où l'avantage a été accordé</p>
</td>
<td width="66">
<p align="center">DATE</p>
</td>
<td width="93">
<p>Format JJ/MM/AAAA</p>
</td>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [A].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td colspan="2" width="194">
<p>AVANT_MONTANT_TTC</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Montant TTC arrondi à l'euro le plus proche</p>
</td>
<td width="66">
<p align="center">MONTANT</p>
</td>
<td width="93"/>
<td width="58">
<p>&gt; 15 000 €<br/>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [A]</p>
</td>
<td width="71">
<p align="center">&lt; 10 €</p>
</td>
</tr>
<tr>
<td width="119">
<p>AVANT_NATURE</p>
</td>
<td width="68"/>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Nature de l'avantage accordé</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [A].</p>
</td>
<td width="71"/>
</tr>
<tr>
<td width="119">
<p>AVANT_CONVENTION_LIE</p>
</td>
<td width="68">
<p align="center">Non</p>
</td>
<td width="69">
<p align="center">Non</p>
</td>
<td width="76">
<p>Intitulé ou référence de la convention éventuellement liée à cet avantage (pas de lien informatique avec la convention)</p>
</td>
<td width="66">
<p align="center">TEXTE</p>
</td>
<td width="93"/>
<td width="58">
<p>Valeur renseignée alors que la valeur du champ LIGNE_TYPE est différente de [A].</p>
</td>
<td width="71"/>
</tr>
</tbody>
</table>

Pièce jointe

<table>
<tbody>
<tr>
<td width="219">
<p align="center">Nom de la pièce jointe </p>
</td>
<td width="442">
<p align="center">ENTREPRISE_IDENTIFIANT#LIGNE_IDENTIFIANT (doit correspondre aux deux premières colonnes du fichier CSV)</p>
</td>
</tr>
<tr>
<td width="219">
<p>Extension</p>
</td>
<td width="442">
<p>pdf</p>
</td>
</tr>
<tr>
<td width="219">
<p>Longueur du nom</p>
</td>
<td width="442">
<p>inférieure à 256 caractères</p>
</td>
</tr>
</tbody>
</table>

Règles de gestion liées à la pièce jointe : si le fichier existe déjà, il est écrasé sans alerte ni erreur.
