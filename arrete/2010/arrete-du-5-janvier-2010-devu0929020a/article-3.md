# Article 3

Le fichier transmis au format texte avec séparateur "point-virgule" est constitué obligatoirement d'une ligne d'en-tête unique comprenant les informations relatives au bailleur et d'une ligne supplémentaire pour chaque logement, les enregistrements logement étant séparés les uns des autres par un saut de ligne.

Le format de la ligne d'en-tête est décrit dans le tableau 1 ci-dessous.

Tableau 1

Format de la ligne d'en-tête

<table>
<tbody>
<tr>
<td>
<p align="center">NUMÉRO<br/>de position</p>
</td>
<td>
<p align="center">
<br/>NATURE DE L'INFORMATION</p>
</td>
<td>
<p align="center">
<br/>FORMAT</p>
</td>
<td>
<p align="center">
<br/>OBLIGATOIRE</p>
</td>
<td>
<p align="center">
<br/>LONGUEUR</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>1</p>
</td>
<td>
<p align="left">
<br/>Année de l'enquête de mise à jour du répertoire</p>
</td>
<td>
<p align="center">
<br/>Date (aaaa)</p>
</td>
<td>
<p align="center">
<br/>O</p>
</td>
<td>
<p align="center">
<br/>4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>2</p>
</td>
<td>
<p align="left">
<br/>Numéro interne au MEDDE de l'organisme propriétaire</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>O</p>
</td>
<td>
<p align="center">
<br/>9</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>3</p>
</td>
<td>
<p align="left">
<br/>Raison sociale du propriétaire</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>O</p>
</td>
<td>
<p align="center">
<br/>Max 100</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>4</p>
</td>
<td>
<p align="left">
<br/>Enseigne du propriétaire (le cas échéant, si l'enseigne est différente de la raison sociale)</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 50</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>5</p>
</td>
<td>
<p align="left">
<br/>Adresse du propriétaire : complément d'identification du destinataire</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 38</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>6</p>
</td>
<td>
<p align="left">
<br/>Adresse du propriétaire : complément d'identification du point géographique</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 38</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>7</p>
</td>
<td>
<p align="left">
<br/>Adresse du propriétaire : numéro et libellé de voie</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 38</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>8</p>
</td>
<td>
<p align="left">
<br/>Adresse du propriétaire : lieudit ou service particulier de distribution</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 38</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>9</p>
</td>
<td>
<p align="left">
<br/>Adresse du propriétaire : code postal et localité de destination</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 38</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>10</p>
</td>
<td>
<p align="left">
<br/>SIRET de l'organisme propriétaire</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>O</p>
</td>
<td>
<p align="center">
<br/>14</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>11</p>
</td>
<td>
<p align="left">
<br/>Nombre d'enregistrements logement du fichier</p>
</td>
<td>
<p align="center">
<br/>Numérique, entier</p>
</td>
<td>
<p align="center">
<br/>O</p>
</td>
<td>
<p align="center">
<br/>Max 6</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>12</p>
</td>
<td>
<p align="left">
<br/>Commentaires</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 200</p>
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
<td>
<p align="center">
<br/>NUMÉRO<br/>de position</p>
</td>
<td>
<p align="center">
<br/>NATURE DE L'INFORMATION</p>
</td>
<td>
<p align="center">
<br/>FORMAT</p>
</td>
<td>
<p align="center">
<br/>MODALITÉS POSSIBLES</p>
</td>
<td>
<p align="center">
<br/>LONGUEUR</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">
<br/>1</p>
</td>
<td align="left" valign="top">
<p align="left">
<br/>Identifiant du logement au répertoire (si le logement existait déjà au 1er janvier de l'année précédente) </p>
</td>
<td align="left" valign="top">
<p align="center">
<br/>Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="center">
<br/>
</p>
</td>
<td align="left" valign="top">
<p align="center">
<br/>10</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>2</p>
</td>
<td>
<p align="left">
<br/>Identifiant du logement dans le système d'information du bailleur </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 100</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">3</p>
</td>
<td align="left" valign="top">
<p align="left">Type de droit du bailleur sur le logement </p>
</td>
<td align="left" valign="top">
<p align="left">Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="left">1 : pleine propriété</p>
<p>2 : bail à réhabilitation</p>
<p>3 : bail emphytéotique</p>
<p>4 : usufruit</p>
<p>5 : bail à construction </p>
</td>
<td align="left" valign="top">
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">4</p>
</td>
<td align="left" valign="top">
<p align="left">Code de la commune où est situé le logement en référence au code officiel géographique </p>
</td>
<td align="left" valign="top">
<p align="center">Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="center">
<br/>
</p>
</td>
<td align="left" valign="top">
<p align="center">5</p>
</td>
</tr>
<tr>
<td>
<p align="center">5</p>
</td>
<td>
<p align="left">Code postal de l'adresse du logement </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">5</p>
</td>
</tr>
<tr>
<td>
<p align="center">6</p>
</td>
<td>
<p align="left">Libellé de la commune où est situé le logement</p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">Max 50</p>
</td>
</tr>
<tr>
<td>
<p align="center">7</p>
</td>
<td>
<p align="left">Numéro de voirie </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">Max 5</p>
</td>
</tr>
<tr>
<td>
<p align="center">8</p>
</td>
<td>
<p align="left">Indice de répétition </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Bis, ter... </p>
</td>
<td>
<p align="center">Max 5</p>
</td>
</tr>
<tr>
<td>
<p align="center">9</p>
</td>
<td>
<p align="left">Type de voie </p>
</td>
<td>
<p align="left">Alphanumérique</p>
</td>
<td>
<p align="left">Rue, place, avenue... </p>
</td>
<td>
<p align="center">Max 15</p>
</td>
</tr>
<tr>
<td>
<p align="center">10</p>
</td>
<td>
<p align="left">Nom de voie</p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">Max 60</p>
</td>
</tr>
<tr>
<td>
<p align="center">11</p>
</td>
<td>
<p align="left">Complément d'identification du logement : numéro d'appartement </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Numéro d'appartement </p>
</td>
<td>
<p align="center">Max 5</p>
</td>
</tr>
<tr>
<td>
<p align="center">12</p>
</td>
<td>
<p align="left">Complément d'identification du logement : numéro de boîte aux lettres </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Numéro de boîte à lettres </p>
</td>
<td>
<p align="center">Max 5</p>
</td>
</tr>
<tr>
<td>
<p align="center">13</p>
</td>
<td>
<p align="left">Complément d'identification du logement : escalier </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Numéro ou lettre d'escalier </p>
</td>
<td>
<p align="center">Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">14</p>
</td>
<td>
<p align="left">Complément d'identification du logement : couloir </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Numéro ou lettre de couloir </p>
</td>
<td>
<p align="center">Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">15</p>
</td>
<td>
<p align="left">Complément d'identification du logement : étage </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Numéro d'étage </p>
</td>
<td>
<p align="center">Max 2</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">16</p>
</td>
<td align="left" valign="top">
<p align="left">Complément d'identification du logement (en cas d'impossibilité de renseigner les champs précédents) </p>
</td>
<td align="left" valign="top">
<p align="center">Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="left">Numéro d'appartement, numéro de boîte aux lettres, escalier, couloir, étage </p>
</td>
<td align="left" valign="top">
<p align="center">Max 50</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">17</p>
</td>
<td align="left" valign="top">
<p align="left">Complément d'identification du bâtiment : entrée </p>
</td>
<td align="left" valign="top">
<p align="center">Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="left">Numéro ou lettre d'entrée du bâtiment </p>
</td>
<td align="left" valign="top">
<p align="center">Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">18</p>
</td>
<td>
<p align="left">Complément d'identification du bâtiment : bâtiment </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Code ou nom du bâtiment </p>
</td>
<td>
<p align="center">Max 50</p>
</td>
</tr>
<tr>
<td>
<p align="center">19</p>
</td>
<td>
<p align="left">Complément d'identification du bâtiment : immeuble </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="left">Code ou nom de l'immeuble </p>
</td>
<td>
<p align="center">Max 50</p>
</td>
</tr>
<tr>
<td>
<p align="center">20</p>
</td>
<td>
<p align="left">Nom du programme immobilier</p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">Max 100</p>
</td>
</tr>
<tr>
<td>
<p align="center">21</p>
</td>
<td>
<p align="left">Lieudit </p>
</td>
<td>
<p align="center">Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">Max 60</p>
</td>
</tr>
<tr>
<td align="left" valign="top">
<p align="center">22</p>
</td>
<td align="left" valign="top">
<p align="left">Logement situé en zone urbaine sensible </p>
</td>
<td align="left" valign="top">
<p align="center">Alphanumérique</p>
</td>
<td align="left" valign="top">
<p align="left">1 : oui</p>
<p>2 : non </p>
</td>
<td align="left" valign="top">
<p align="center">1</p>
</td>
</tr>
<tr>
<td align="left" valign="middle">
<p align="center">23</p>
</td>
<td align="left" valign="middle">
<p align="left">Type de construction </p>
</td>
<td align="left" valign="middle">
<p align="left">Alphabétique majuscule</p>
</td>
<td align="left" valign="middle">
<p align="left">C : collectif</p>
<p>I : individuel </p>
</td>
<td align="left" valign="middle">
<p align="center">1</p>
</td>
</tr>
<tr>
<td>
<p align="center">24</p>
</td>
<td>
<p align="left">Nombre de pièces principales du logement</p>
</td>
<td>
<p align="left">Alphanumérique</p>
</td>
<td>
<p align="left">Entre 1 et 9 </p>
</td>
<td>
<p align="center">1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>25</p>
</td>
<td>
<p align="center">
<br/>Surface habitable (m²) </p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi au mètre carré </p>
</td>
<td>
<p align="center">
<br/>Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>26</p>
</td>
<td>
<p align="center">
<br/>Année d'achèvement de la construction </p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>aaaa </p>
</td>
<td>
<p align="center">
<br/>4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>27</p>
</td>
<td>
<p align="center">
<br/>Année de la première mise en location du logement dans le parc locatif social </p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>aaaa </p>
</td>
<td>
<p align="center">
<br/>4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>28</p>
</td>
<td>
<p align="center">
<br/>Année d'entrée du logement dans le patrimoine du bailleur </p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>aaaa </p>
</td>
<td>
<p align="center">
<br/>4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>29</p>
</td>
<td>
<p align="center">
<br/>Mode d'entrée du logement dans le patrimoine du bailleur </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : construction par l'organisme</p>
<p>2 : acquisition avec travaux</p>
<p>3 : acquisition sans travaux</p>
<p>4 : acquisition en VEFA </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>30</p>
</td>
<td>
<p align="center">
<br/>Raison sociale du précédent propriétaire si le logement a été acquis au cours de l'année civile précédant l'enquête ou au 1er janvier (mode d'entrée du logement dans le patrimoine = 2 ou 3) </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 100</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>31</p>
</td>
<td>
<p align="center">
<br/>SIRET du précédent propriétaire si le logement a été acquis au cours de l'année civile précédant l'enquête ou au 1er janvier (mode d'entrée du logement dans le patrimoine = 2 ou 3) </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>14</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>32</p>
</td>
<td>
<p align="center">
<br/>Financement initial du logement locatif social </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>Avant 1977 (1983 dans les DOM) :</p>
<p>50 : HBM</p>
<p>51 : PLR/PSR</p>
<p>52 : HLM/O</p>
<p>53 : ILM</p>
<p>54 : ILN</p>
<p>55 : prêts spéciaux du CFF</p>
<p>99 : autre financement</p>
<p>A partir de 1977 (1983 dans les DOM) :</p>
<p>10 : PLA d'intégration (LLTS dans les DOM)</p>
<p>11 : PLA loyer minoré/PLA très social/PLA insertion</p>
<p>12 : PLA ordinaire</p>
<p>13 : PLUS (LLS dans les DOM)</p>
<p>14 : PLS/PPLS/PCLS /PLA CFF</p>
<p>15 : PAP locatif</p>
<p>16 : PLI</p>
<p>17 : PCL (conventionné ou non)</p>
<p>49 : autre financement </p>
</td>
<td>
<p align="center">
<br/>2</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>33</p>
</td>
<td>
<p align="center">
<br/>Si financement autre, libellé de ce financement </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 30</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>34</p>
</td>
<td>
<p align="center">
<br/>Conventionnement du logement à l'APL </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : oui</p>
<p>2 : non </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>35</p>
</td>
<td>
<p align="center">
<br/>Si logement conventionné à l'APL, numéro de la convention </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 35</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>36</p>
</td>
<td>
<p align="center">
<br/>Si logement conventionné à l'APL, date de prise d'effet de la convention </p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>jj/mm/aaaa </p>
</td>
<td>
<p align="center">
<br/>10</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>37</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, motif de sortie du patrimoine du bailleur au cours de l'année civile précédant l'enquête</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : vente à l'occupant</p>
<p>2 : vente à un autre bailleur social</p>
<p>3 : autre vente</p>
<p>4 : démolition</p>
<p>5 : autre motif</p>
<p>9 : sans objet</p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>38</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, si le logement n'existe plus au 1er janvier de l'année de l'enquête mais que la surface correspondante est toujours dans le patrimoine du bailleur à cette date </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : changement d'usage du logement</p>
<p>2 : logement fusionné avec un autre logement, ou scindé pour créer deux logements ou plus </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>39</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, si le logement n'existait pas au 1er janvier de l'année précédant l'enquête mais que la surface correspondante était déjà dans le patrimoine du bailleur à cette date</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : logement créé à partir de locaux antérieurement affectés à un autre usage</p>
<p>2 : logement créé par fusion ou éclatement de logements existants </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>40</p>
</td>
<td>
<p align="center">
<br/>Mode d'occupation au 1er janvier de l'année en cours </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : loué avec contrat de location (hors bail professionnel)</p>
<p>2 : proposé à la location mais vacant</p>
<p>3 : vide (en cours ou en attente de gros travaux, de vente ou de démolition)</p>
<p>4 : logement pris en charge par une association</p>
<p>5 : logement occupé avec/sans contrepartie financière (dont logement de gardien)</p>
<p>9 : sans objet </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>41</p>
</td>
<td>
<p align="center">
<br/>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, date de prise d'effet du bail en cours</p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>mm/aaaa </p>
</td>
<td>
<p align="center">
<br/>7</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>42</p>
</td>
<td>
<p align="center">
<br/>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, mode d'évaluation de la surface retenue pour le calcul du loyer </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : utile</p>
<p>2 : corrigée</p>
<p>3 : habitable</p>
<p>9 : sans objet </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>43</p>
</td>
<td>
<p align="center">
<br/>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, surface totale dans le mode retenu pour l'application du loyer (m²) </p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi au mètre carré</p>
<p>999 : sans objet </p>
</td>
<td>
<p align="center">
<br/>Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>44</p>
</td>
<td>
<p align="center">
<br/>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, montant du loyer en principal (€) quittancé au titre du mois de janvier de l'année en cours </p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
<p>9999 : sans objet </p>
</td>
<td>
<p align="center">
<br/>Max 4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>45</p>
</td>
<td>
<p align="center">
<br/>Si le logement est occupé avec contrat de location au 1er janvier de l'année de l'enquête, montants des loyers accessoires (€) quittancés au titre du mois de janvier de l'année en cours </p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
<p>999 : sans objet </p>
</td>
<td>
<p align="center">
<br/>Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>46</p>
</td>
<td>
<p align="center">
<br/>Contribution pour le partage d'économie de charges (€) quittancée au titre du mois de janvier de l'année en cours</p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
<p>999 : sans objet </p>
</td>
<td>
<p align="center">
<br/>Max 3</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>47</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, plafond de ressources correspondant au titre de la CUS</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>11 : PLAI</p>
<p>13 : PLUS</p>
<p>14 : PLS</p>
<p>16 : PLI</p>
</td>
<td>
<p align="center">
<br/>2</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>48</p>
</td>
<td>
<p align="center">
<br/>Date d'établissement du dernier diagnostic de performance énergétique </p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>mm/aaaa</p>
<p>01/1900 : diagnostic non réalisé </p>
</td>
<td>
<p align="center">
<br/>7</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>49</p>
</td>
<td>
<p align="center">
<br/>Si un diagnostic de performance énergétique a été réalisé, classe de consommation d'énergie </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>A à G </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>50</p>
</td>
<td>
<p align="center">
<br/>Si un diagnostic de performance énergétique a été réalisé, classe de l'impact des consommations d'énergie sur l'effet de serre</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>A à G </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>51</p>
</td>
<td>
<p align="center">
<br/>Si logement ordinaire concerné par l'inventaire des logements sociaux, articles L. 302-5 et L. 302-6 du CCH, année d'expiration de la convention</p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>aaaa </p>
</td>
<td>
<p align="center">
<br/>4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>52</p>
</td>
<td>
<p align="center">
<br/>Si logement ordinaire concerné par l'inventaire des logements sociaux, articles L. 302-5 et L. 302-6 du CCH, alinéa d'affectation du logement </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 à 3 </p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>53</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, numéro interne au MEDDE de l'organisme gestionnaire</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>9</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>54</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, code identifiant le segment de patrimoine de la convention d'utilité sociale </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 20</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>55</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, libellé court du segment de patrimoine défini dans la convention d'utilité sociale</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>Max 50</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>56</p>
</td>
<td>
<p align="center">
<br/>Si logement conventionné à l'APL, montant actualisé du loyer mensuel maximal (€) résultant de la convention APL</p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
</td>
<td>
<p align="center">
<br/>Max 4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>57</p>
</td>
<td>
<p align="center">
<br/>Le cas échéant, si loyer des immeubles régi par la convention d'utilité sociale, montant actualisé du loyer mensuel maximal (€) résultant de la convention d'utilité sociale</p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
</td>
<td>
<p align="center">
<br/>Max 4</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>58</p>
</td>
<td>
<p align="center">
<br/>Si le logement a été vendu au cours de l'année civile précédant l'enquête, type de vente</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>01 : vente à un locataire occupant</p>
<p>02 : vente à un conjoint, ascendant, descendant du locataire occupant</p>
<p>03 : vente à un locataire de l'organisme</p>
<p>04 : vente à un gardien d'immeuble</p>
<p>05 : vente à une autre personne physique</p>
<p>06 : vente à un organisme HLM</p>
<p>07 : vente à une SEM</p>
<p>08 : vente à une collectivité territoriale</p>
<p>09 : vente à un organisme qui bénéficie de l'agrément prévu à l'article L. 365-2</p>
<p>10 : vente à une autre personne morale</p>
</td>
<td>
<p align="center">
<br/>2</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>59</p>
</td>
<td>
<p align="center">
<br/>Si logement relevant des dispositions de l'article L. 443-11, mise en commercialisation effective au cours de l'année civile précédant l'enquête (hors cession de logements entre bailleurs sociaux)</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : oui</p>
<p>2 : non</p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>60</p>
</td>
<td>
<p align="center">
<br/>Si logement relevant des dispositions de l'article L. 443-11 et vendu au cours de l'année civile précédant l'enquête, prix de vente du logement</p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
</td>
<td>
<p align="center">
<br/>Max 7</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>61</p>
</td>
<td>
<p align="center">
<br/>Si logement relevant des dispositions de l'article L. 443-11 et vendu au cours de l'année civile précédant l'enquête, produit financier net</p>
</td>
<td>
<p align="center">
<br/>Numérique</p>
</td>
<td>
<p align="center">
<br/>Entier, arrondi à l'euro</p>
</td>
<td>
<p align="center">
<br/>Max 6</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>62</p>
</td>
<td>
<p align="center">
<br/>Dernière date à laquelle le logement a pu être offert à la location</p>
</td>
<td>
<p align="center">
<br/>Date</p>
</td>
<td>
<p align="center">
<br/>mm/aaaa </p>
</td>
<td>
<p align="center">
<br/>7</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>63</p>
</td>
<td>
<p align="center">
<br/>Pour les logements relevant de l'article L. 441-1, contingent d'appartenance pour les logements réservés au sens de l'article R. 441-5</p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>1 : état fonctionnaires et agents publics</p>
<p>2 : état prioritaire au sens de l'article L. 441-1</p>
<p>3 : employeur et organismes collecteurs du 1 % Logement</p>
<p>4 : collectivités territoriales, leurs établissements publics et EPCI</p>
<p>5 : réservation de l'Etat pour le logement des fonctionnaires au moyen des conventions prévues aux articles R. 314-4, R. 314-16 ou R. 314-21</p>
<p>6 : autres réservataires</p>
<p>7 : non réservé</p>
</td>
<td>
<p align="center">
<br/>1</p>
</td>
</tr>
<tr>
<td>
<p align="center">
<br/>64</p>
</td>
<td>
<p align="center">
<br/>Commentaire </p>
</td>
<td>
<p align="center">
<br/>Alphanumérique</p>
</td>
<td>
<p align="center">
<br/>
</p>
</td>
<td>
<p align="center">
<br/>200</p>
</td>
</tr>
</tbody>
</table>
