# Article 

ANNEXE

FORMAT DES FICHIERS INFORMATIQUES ET CONTENU DES CATÉGORIES D'INFORMATIONS

I. - Le fichier informatique est au format texte avec séparateur  point-virgule .

II. - Chaque fichier transmis par le professionnel est nommé comme suit :

[ANNEE]_[IDENTPRO]_[N_FIC].CSV,

avec :

ANNEE = année en cours sur quatre positions ;

IDENTPRO = identifiant du professionnel sur X positions ;

N_FIC = numéro du fichier dans l'envoi, sur trois positions. Ex : 001 pour le premier fichier de l'envoi et 002 pour le second.

Dans le cas d'une transmission sous forme d'une archive ZIP contenant un ou plusieurs fichiers, l'archive est nommée sous la forme [ANNEE]_[IDENTPRO]_[N_FIC].ZIP.

Lors de l'envoi, le professionnel indique les noms, prénoms, qualité et adresse électronique des personnes que l'observatoire local des loyers compétent ou l'association nationale mentionnée au premier alinéa de l'article 1er peut contacter pour toute précision sur les fichiers et leur contenu.

III. - Le fichier transmis au format texte avec séparateur  point-virgule  est constitué obligatoirement d'une ligne d'en-tête unique comprenant les informations relatives au professionnel et d'une ligne supplémentaire pour chaque logement, les enregistrements logement étant séparés les uns des autres par un saut de ligne.

Le format et le contenu de la ligne d'en-tête sont décrits dans le tableau 1 ci-dessous.

Le format et le contenu des lignes logement sont décrits dans le tableau 2 ci-dessous.

Tableau 1. - Format et contenu de la ligne d'en-tête

<table>
<tbody>
<tr>
<td>
<p align="center"> NUMÉRO <br/>de position</p>
</td>
<td>
<p align="center"> NATURE DE L'INFORMATION</p>
</td>
<td>
<p align="center"> FORMAT</p>
</td>
<td>
<p align="center"> OBLIGATOIRE</p>
</td>
<td>
<p align="center"> LONGUEUR</p>
</td>
</tr>
<tr>
<td align="center" valign="middle">1<br/>
</td>
<td align="left" valign="middle">Année de l'extraction du système d'information du professionnel<br/>
</td>
<td align="center" valign="middle">AAAA<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">2<br/>
</td>
<td align="left" valign="middle">SIRET de l'organisme propriétaire<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">14<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">3<br/>
</td>
<td align="left" valign="middle">Nombre d'enregistrements logement du fichier<br/>
</td>
<td align="center" valign="middle">Numérique, entier<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle"/>
</tr>
<tr>
<td align="center" valign="middle">4<br/>
</td>
<td align="left" valign="middle">Commentaires<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 200<br/>
</td>
</tr>
</tbody>
</table>

Tableau 2. - Format et contenu des enregistrements logement

<table>
<tbody>
<tr>
<td>
<p align="center"> NUMÉRO <br/>de position</p>
</td>
<td>
<p align="center"> NATURE DE L'INFORMATION</p>
</td>
<td>
<p align="center"> FORMAT</p>
</td>
<td>
<p align="center"> MODALITÉS POSSIBLES</p>
</td>
<td>
<p align="center"> OBLIGATOIRE</p>
</td>
<td>
<p align="center"> LONGUEUR</p>
</td>
</tr>
<tr>
<td align="center" valign="middle">1<br/>
</td>
<td valign="middle">Identifiant du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 50<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">2<br/>
</td>
<td valign="middle">Source de la donnée<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left">1 : administrateurs de biens<br/>2 : agences immobilières<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">3<br/>
</td>
<td valign="middle">Mode de collecte<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : transfert de fichiers<br/>2 : données centralisées<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">4<br/>
</td>
<td valign="middle">Date d'enquête<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">JJMMAA<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">6<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">4b<br/>
</td>
<td valign="middle">Date d'enquête précédente<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">JJMMAA<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">6<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5<br/>
</td>
<td valign="middle">Numéro de voirie de l'adresse du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5b<br/>
</td>
<td valign="middle">Indice de répétition<br/>
</td>
<td align="center" valign="middle">Alphabétique <br/>majuscule<br/>
</td>
<td align="left" valign="middle">B : bis<br/>T : ter<br/>Q : quater<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5c<br/>
</td>
<td valign="middle">Type de voie<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">Rue, place, avenue…<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5d<br/>
</td>
<td valign="middle">Nom de voie<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 40<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5e<br/>
</td>
<td valign="middle">Complément d'identification du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 40<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5f<br/>
</td>
<td valign="middle">Code postal de l'adresse du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">5<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">5g<br/>
</td>
<td valign="middle">Libellé de la commune où est situé le logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 35<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">6<br/>
</td>
<td valign="middle">Code de la commune où est situé le logement en référence au code officiel géographique<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">5<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">6b<br/>
</td>
<td valign="middle">Code de la zone dans le zonage défini par l'observatoire local<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">2<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">6c<br/>
</td>
<td valign="middle">Numéro de l'IRIS où est situé le logement en référence au code officiel géographique<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">6d<br/>
</td>
<td valign="middle">Code de la section cadastrale où est situé le logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">2<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">6e<br/>
</td>
<td valign="middle">Code de la parcelle cadastrale où est situé le logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">7<br/>
</td>
<td valign="middle">Date de référence (si autre que 1er janvier)<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">JJMM<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">8<br/>
</td>
<td valign="middle">Numéro de la carte G ou T du professionnel<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 10<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">8b<br/>
</td>
<td valign="middle">Numéro de gestion du logement dans le système d'information du professionnel<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 20<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">8c<br/>
</td>
<td valign="middle">Raison sociale du professionnel<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 20<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">21<br/>
</td>
<td valign="middle">Remarques destinées au centre national de traitement<br/>
</td>
<td align="center" valign="middle">Alphabétique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 60<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">31<br/>
</td>
<td valign="middle">Type d'habitat<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : individuel<br/>2 : collectif<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">32<br/>
</td>
<td valign="middle">Epoque de construction<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : Avt 1919<br/>2 : 1919-1945<br/>4 : 1946-1970<br/>5 : 1971-1990<br/>6 : 1991-2005<br/>7 : Ap. 2005<br/>(à défaut, 3 : Avt 1946)<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">33<br/>
</td>
<td valign="middle">Année d'achèvement de la construction<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">AAAA<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">4<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">34<br/>
</td>
<td valign="middle">Type de propriété<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : monopropriété<br/>2 : copropriété<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">35<br/>
</td>
<td valign="middle">Présence d'un ascenseur<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">35b<br/>
</td>
<td valign="middle">Présence d'un gardien<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">35c<br/>
</td>
<td valign="middle">Présence d'un interphone<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">35d<br/>
</td>
<td valign="middle">Présence d'un digicode<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">35e<br/>
</td>
<td valign="middle">Présence d'un vidéophone<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">41<br/>
</td>
<td valign="middle">Nombre de pièces principales du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 2<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">42<br/>
</td>
<td valign="middle">Surface habitable (m2)<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td valign="middle">Entier, arrondi au mètre carré<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 3<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">43<br/>
</td>
<td valign="middle">Etage du logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">Numéro d'étage<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 2<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">44<br/>
</td>
<td valign="middle">Parking, si inclus dans le loyer<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">44b<br/>
</td>
<td valign="middle">Balcon<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">44c<br/>
</td>
<td valign="middle">Jardin<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">45<br/>
</td>
<td valign="middle">Nombre de WC<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">45b<br/>
</td>
<td valign="middle">Nombre de SdB<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">46<br/>
</td>
<td valign="middle">Type de chauffage<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : individuel<br/>2 : collectif<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">47<br/>
</td>
<td valign="middle">Type de propriétaire<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : particulier<br/>2 : personne morale<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">50<br/>
</td>
<td valign="middle">Si un diagnostic de performance énergétique a été réalisé, classe de consommation d'énergie<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td valign="middle">A à G<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">51<br/>
</td>
<td valign="middle">Type de location<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : vide<br/>2 : meublé<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">52<br/>
</td>
<td valign="middle">Type de gestion<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : déléguée<br/>2 : directe<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">53<br/>
</td>
<td valign="middle">Catégorie de location<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : libre<br/>2 : conventionnée<br/>3 : défiscalisée<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">1<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">54<br/>
</td>
<td valign="middle">Date d'emménagement du locataire dans le logement<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">JJMMAAAA<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">8<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">54b<br/>
</td>
<td valign="middle">Date du bail<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="center" valign="middle">JJMMAAAA<br/>
</td>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">8<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">55<br/>
</td>
<td valign="middle">Première location si emménagé depuis le 1er janvier N - 1<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle">1 : oui<br/>2 : non<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
</tr>
<tr>
<td align="center" valign="middle">56<br/>
</td>
<td valign="middle">Loyer mensuel hors charges à la même date l'année N - 1 en euros<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 8 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">56b<br/>
</td>
<td valign="middle">Loyer mensuel hors charges à la date d'enquête en euros<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="center" valign="middle">O<br/>
</td>
<td align="center" valign="middle">Max 8 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">57<br/>
</td>
<td valign="middle">Loyer mensuel hors charges à la même date de référence de l'année N - 1 en euros (normalement 1er janvier)<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 8 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">57b<br/>
</td>
<td valign="middle">Loyer mensuel hors charges à la date de référence en euros (normalement 1er janvier)<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 8 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">58<br/>
</td>
<td valign="middle">Provisions mensuelles pour charges de l'année N - 1 en euros<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 6 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">58b<br/>
</td>
<td valign="middle">Provisions mensuelles pour charges en euros<br/>
</td>
<td align="center" valign="middle">Numérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 6 (dont  , )<br/>
</td>
</tr>
<tr>
<td align="center" valign="middle">59<br/>
</td>
<td valign="middle">Commentaire<br/>
</td>
<td align="center" valign="middle">Alphanumérique<br/>
</td>
<td align="left" valign="middle"/>
<td align="left" valign="middle"/>
<td align="center" valign="middle">Max 200<br/>
</td>
</tr>
</tbody>
</table>
