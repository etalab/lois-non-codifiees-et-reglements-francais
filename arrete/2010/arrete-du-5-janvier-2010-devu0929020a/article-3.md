# Article 3

Le fichier transmis au format texte avec séparateur point-virgule est constitué obligatoirement d'une ligne d'en-tête unique comprenant les informations relatives au bailleur et d'une ligne supplémentaire pour chaque logement, les enregistrements logement étant séparés les uns des autres par un saut de ligne.

Le format de la ligne d'en-tête est décrit dans le tableau 1 ci-dessous.

Tableau 1

Format de la ligne d'en-tête

<table>
<tbody>
<tr>
<td width="386">
<p align="center">NATURE DE L'INFORMATION</p>
</td>
<td width="110">
<p align="center">FORMAT</p>
</td>
<td width="83">
<p align="center">OBLIGATOIRE</p>
</td>
<td width="82">
<p align="center">LONGUEUR</p>
</td>
</tr>
<tr>
<td width="386">
<p>Année de l'enquête de mise à jour du répertoire </p>
</td>
<td width="110">
<p align="center">Date (aaaa)</p>
</td>
<td width="83">
<p align="center">O</p>
</td>
<td width="82">
<p align="center">4</p>
</td>
</tr>
<tr>
<td width="386">
<p>Numéro interne au MEEDDM de l'organisme propriétaire </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td width="83">
<p align="center">O</p>
</td>
<td width="82">
<p align="center">9</p>
</td>
</tr>
<tr>
<td width="386">
<p>Raison sociale du propriétaire </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td width="83">
<p align="center">O</p>
</td>
<td width="82">
<p align="center">Max 100</p>
</td>
</tr>
<tr>
<td width="386">
<p>Enseigne du propriétaire (le cas échéant, si l'enseigne est différente de la raison sociale) </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 50</p>
</td>
</tr>
<tr>
<td width="386">
<p>Adresse du propriétaire : complément d'identification du destinataire </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 38</p>
</td>
</tr>
<tr>
<td width="386">
<p>Adresse du propriétaire : complément d'identification du point géographique </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 38</p>
</td>
</tr>
<tr>
<td width="386">
<p>Adresse du propriétaire : numéro et libellé de voie </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 38</p>
</td>
</tr>
<tr>
<td width="386">
<p>Adresse du propriétaire : lieudit ou service particulier de distribution </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 38</p>
</td>
</tr>
<tr>
<td width="386">
<p>Adresse du propriétaire : code postal et localité de destination </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 38</p>
</td>
</tr>
<tr>
<td width="386">
<p>SIRET de l'organisme propriétaire </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td width="83">
<p align="center">O</p>
</td>
<td width="82">
<p align="center">14</p>
</td>
</tr>
<tr>
<td width="386">
<p>Nombre d'enregistrements logement du fichier </p>
</td>
<td width="110">
<p align="center">Numérique, entier</p>
</td>
<td width="83">
<p align="center">O</p>
</td>
<td width="82">
<p align="center">Max 6</p>
</td>
</tr>
<tr>
<td width="386">
<p>Commentaires </p>
</td>
<td width="110">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="83">
<br/>
</td>
<td width="82">
<p align="center">Max 200</p>
</td>
</tr>
</tbody>
</table>

Le format des lignes logement est décrit dans le tableau 2 ci-dessous.

Tableau 2

Format des enregistrements logement

<table>
<tbody>
<tr>
<td width="331">
<p align="center">NATURE DE L'INFORMATION</p>
</td>
<td width="120">
<p align="center">FORMAT</p>
</td>
<td width="120">
<p align="center">MODALITÉS possibles</p>
</td>
<td width="90">
<p align="center">LONGUEUR maximale</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Identifiant du logement au répertoire (si le logement existait déjà au 1er janvier de l'année précédente) </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">10</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Identifiant du logement dans le système d'information du bailleur </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">100</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Type de droit du bailleur sur le logement </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : Pleine propriété</p>
<p>2 : Bail à réhabilitation</p>
<p>3 : Bail emphytéotique</p>
<p>4 : Usufruit</p>
<p>5 : Bail à construction</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Code de la commune où est situé le logement en référence au code officiel géographique </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Code postal de l'adresse du logement </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Libellé de la commune où est situé le logement </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">50</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Numéro de voirie </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Indice de répétition </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Bis, ter...</p>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Type de voie </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Rue, place, avenue...</p>
</td>
<td valign="top" width="90">
<p align="center">15</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Nom de voie </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">60</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement : numéro d'appartement </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro d'appartement</p>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement : numéro de boîte aux lettres </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro de boîte à lettres</p>
</td>
<td valign="top" width="90">
<p align="center">5</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement : escalier </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro ou lettre d'escalier</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement : couloir </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro ou lettre de couloir</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement : étage </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro d'étage</p>
</td>
<td valign="top" width="90">
<p align="center">2</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du logement (en cas d'impossibilité de renseigner les champs précédents) </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro d'appartement, numéro de boîte aux lettres, escalier, couloir, étage</p>
</td>
<td valign="top" width="90">
<p align="center">50</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du bâtiment : entrée </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Numéro ou lettre d'entrée du bâtiment</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du bâtiment : bâtiment </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Code ou nom du bâtiment</p>
</td>
<td valign="top" width="90">
<p align="center">50</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du bâtiment : immeuble </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Code ou nom de l'immeuble</p>
</td>
<td valign="top" width="90">
<p align="center">50</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Complément d'identification du bâtiment (en cas d'impossibilité de renseigner les champs précédents) </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Entrée, bâtiment, immeuble</p>
</td>
<td valign="top" width="90">
<p align="center">100</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Lieudit </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">60</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Logement situé en zone urbaine sensible </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : oui </p>
<p>2 : non</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Type de construction </p>
</td>
<td valign="top" width="120">
<p align="center">Alphabétique</p>
</td>
<td valign="top" width="120">
<p>C : collectif</p>
<p>I : individuel</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Nombre de pièces principales du logement </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Entre 1 et 9</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Surface habitable (m2) </p>
</td>
<td valign="top" width="120">
<p align="center">Numérique</p>
</td>
<td valign="top" width="120">
<p>Entier, arrondi au mètre carré</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Année d'achèvement de la construction </p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">4</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Année de la première mise en location du logement dans le parc locatif social </p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">4</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Année d'entrée du logement dans le patrimoine du bailleur </p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">4</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Mode d'entrée du logement dans le patrimoine du bailleur </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : construction par l'organisme</p>
<p>2 : acquisition avec travaux</p>
<p>3 : acquisition sans travaux</p>
<p>4 : acquisition en VEFA</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Raison sociale du précédant propriétaire si le logement a été acquis au cours de l'année civile précédant l'enquête ou au 1er janvier (mode d'entrée du logement dans le patrimoine = 2 ou 3) </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">100</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>SIRET du précédant propriétaire si le logement a été acquis au cours de l'année civile précédant l'enquête ou au 1er janvier (mode d'entrée du logement dans le patrimoine = 2 ou 3) </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">14</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Financement initial du logement locatif social </p>
</td>
<td valign="top" width="120">
<p>Alphanumérique </p>
</td>
<td valign="top" width="120">
<p>Avant 1977 (1983 dans les DOM) :</p>
<p>50 : HBM</p>
<p>51 : PLR/PSR</p>
<p>52 : HLM/O</p>
<p>53 : ILM</p>
<p>54 : ILN</p>
<p>55 : prêts spéciaux du CFF</p>
<p>99 : autre financement</p>
<p>A partir de 1977 (1983 dans les DOM) :</p>
<p>10 : PLA d'intégration (LLTS dans les DOM) 11 : PLA LM/PLATS/PLA Insertion (LLSS dans les DOM)</p>
<p>12 : PLA social/PLA ordinaire</p>
<p>13 : PLUS (LLS dans les DOM)</p>
<p>14 : PLS/PPLS/PCLS-CFF /PLA CFF</p>
<p>15 : PAP locatif</p>
<p>16 : PLI</p>
<p>17 : PCL (conventionné ou non)</p>
<p>49 : autre financement </p>
</td>
<td valign="top" width="90">
<p>2 </p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si financement  autre , libellé de ce financement</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">30</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Conventionnement du logement à l'APL</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : oui 2 : non</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si logement conventionné à l'APL, numéro de la convention</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">35</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si logement conventionné à l‘APL, date de prise d'effet de la convention</p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>jj/mm/aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">10</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Le cas échéant, motif de sortie du patrimoine du bailleur au cours de l'année civile précédant l'enquête</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : vente à l'occupant</p>
<p>2 : vente à un autre bailleur social</p>
<p>3 : autre vente</p>
<p>4 : démolition</p>
<p>5 : autre motif</p>
<p>9 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Le cas échéant, si le logement n'existe plus au 1er janvier de l'année de l'enquête mais que la surface correspondante est toujours dans le patrimoine du bailleur à cette date</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : changement d'usage du logement</p>
<p>2 : logement fusionné avec un autre logement, ou scindé pour créer deux logements ou plus</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Le cas échéant, si le logement n'existait pas au 1er janvier de l'année précédant l'enquête mais que la surface correspondante était déjà dans le patrimoine du bailleur à cette date</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : logement créé à partir de locaux antérieurement affectés à un autre usage</p>
<p>2 : logement créé par fusion ou éclatement de logements existants</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Mode d'occupation au 1er janvier de l'année en cours </p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : loué avec contrat de location (hors bail professionnel),</p>
<p>2 : proposé à la location mais vacant</p>
<p>3 : vide (en cours ou en attente de gros travaux, de vente ou de démolition)</p>
<p>4 : logement pris en charge par une association</p>
<p>5 : logement occupé avec/sans contrepartie financière (dont logement de gardien)</p>
<p>9 : sans objet </p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, date de prise d'effet du bail en cours</p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>mm/aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">7</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, mode d'évaluation de la surface retenu pour le calcul du loyer</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 : utile</p>
<p>2 : corrigée</p>
<p>3 : habitable</p>
<p>9 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, surface totale dans le mode retenu pour l'application du loyer (m2)</p>
</td>
<td valign="top" width="120">
<p align="center">Numérique</p>
</td>
<td valign="top" width="120">
<p>Entier, arrondi au mètre carré</p>
<p>999 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, montant du loyer en principal (€) quittancé au titre du mois de janvier de l'année en cours</p>
</td>
<td valign="top" width="120">
<p align="center">Numérique</p>
</td>
<td valign="top" width="120">
<p>Entier, arrondi à l'euro</p>
<p>9999 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">4</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p align="center">Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, montants des loyers accessoires (€) quittancés au titre du mois de janvier de l'année en cours</p>
</td>
<td valign="top" width="120">
<p align="center">Numérique</p>
</td>
<td valign="top" width="120">
<p>Entier, arrondi à l'euro</p>
<p>999 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Contribution pour le partage d'économie de charges (€) quittancée au titre du mois de janvier de l'année en cours</p>
</td>
<td valign="top" width="120">
<p align="center">Numérique</p>
</td>
<td valign="top" width="120">
<p>Entier, arrondi à l'euro</p>
<p>999 : sans objet</p>
</td>
<td valign="top" width="90">
<p align="center">3</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Catégorie de financement auquel est rattaché le logement au titre du CUS</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>Avant 1977 (1983 dans les DOM) :</p>
<p>50 : HBM</p>
<p>51 : PLR/PSR</p>
<p>52 : HLM/O</p>
<p>53 : ILM</p>
<p>54 : ILN</p>
<p>55 : prêts spéciaux du CFF</p>
<p>99 : autre financement</p>
<p>A partir de 1977 (1983 dans les DOM) :</p>
<p>10 : PLA d'intégration (LLTS dans les DOM)</p>
<p>11 : PLA LM/PLATS/PLA Insertion (LLSS dans les DOM)</p>
<p>12 : PLA social/PLA ordinaire</p>
<p>13 : PLUS (LLS dans les DOM)</p>
<p>14 : PLS/PPLS/PCLS­CFF/PLA CFF</p>
<p>15 : PAP locatif</p>
<p>16 : PLI</p>
<p>17 : PCL (conventionné ou non)</p>
<p>49 : autre financement</p>
</td>
<td valign="top" width="90">
<p align="center">2</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Date d'établissement du dernier diagnostic de performance énergétique</p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>mm/aaaa 01/1900 : diagnostic non réalisé</p>
</td>
<td valign="top" width="90">
<p align="center">7</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si un diagnostic de performance énergétique a été réalisé, classe de consommation d'énergie</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>A à G</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si un diagnostic de performance énergétique a été réalisé, classe de l'impact des consommations d'énergie sur l'effet de serre</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>A à G</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si logement ordinaire concerné par l'inventaire des logements sociaux, articles L. 305-5 et L. 302-6 du CCH, année d'expiration de la convention</p>
</td>
<td valign="top" width="120">
<p align="center">Date</p>
</td>
<td valign="top" width="120">
<p>aaaa</p>
</td>
<td valign="top" width="90">
<p align="center">4</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Si logement ordinaire concerné par l'inventaire des logements sociaux, articles L. 305-5 et L. 302-6 du CCH, alinéa d'affectation du logement</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<p>1 à 3</p>
</td>
<td valign="top" width="90">
<p align="center">1</p>
</td>
</tr>
<tr>
<td valign="top" width="331">
<p>Commentaire</p>
</td>
<td valign="top" width="120">
<p align="center">Alphanumérique</p>
</td>
<td valign="top" width="120">
<br/>
</td>
<td valign="top" width="90">
<p align="center">200</p>
</td>
</tr>
</tbody>
</table>
