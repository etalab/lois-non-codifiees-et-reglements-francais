# Article Annexe

Pour toute analyse automatisée, l'identification positive des échantillons à tester doit être réalisée au moyen d'un automate de distribution, par lecture du code à barres imprimé sur l'étiquette de chaque échantillon.

Lorsque le laboratoire traite des échantillons en provenance d'autres établissements de transfusion sanguine, leur identification et leur enregistrement doivent permettre de remonter au donneur et aux résultats des analyses biologiques et tests de dépistage pratiqués sur les dons antérieurs.

L'automate d'identification positive des échantillons et les lecteurs de réactions doivent être connectés à un ordinateur associant de façon automatique et univoque le code à barres précédemment identifié et le résultat brut de l'échantillon correspondant. La lecture de l'identifiant doit être contrôlée et auto-validée.

IV.2.1. Pour les analyses immuno-hématologiques

Le logiciel doit interpréter les résultats en fonction des valeurs seuils, valider chaque série de réactions à l'aide des témoins et des contrôles, valider le déroulement effectif de la réaction et interpréter les échantillons en terme de résultats nets. Ces résultats sont de type Cohérent, Incohérent ou Invalide.

Un résultat d'analyse est considéré comme Incohérent par le système informatique, en cas d'anomalie. Par exemple, la présence simultanée d'un antigène et de l'anticorps correspondant (groupage ABO et identification des anticorps antiérythrocytaires) ou l'absence de deux antigènes antithétiques (phénotypage Rh-K et autres phénotypages) génère un signal de type Incohérent.

Un résultat d'analyse est considéré comme Invalide par le système informatique lorsque le déroulement effectif de la réaction n'est pas validé.

Le logiciel doit constituer un fichier imprimable permettant d'associer pour chaque échantillon : le numéro de don, le type d'analyse, la date de l'analyse, les noms et les numéros de lots des réactifs, la référence du distributeur et du lecteur utilisés, le résultat brut et le résultat net. Ce fichier sert au transfert des résultats et à leur archivage.

IV.2.2 Pour les tests de dépistage des maladies transmissibles

Le logiciel doit calculer les valeurs seuils, valider chaque support de réaction à l'aide des témoins et des contrôles, valider le déroulement effectif de la réaction et interpréter les échantillons en terme de résultats nets. Ces résultats nets sont de type Négatif, Réactif initial ou Invalide.

Un résultat d'analyse est considéré comme Invalide par le système informatique lorsqu'il n'est pas validé soit en raison du déroulement de l'analyse biologique, soit par l'analyse des témoins et contrôles précités.

Un résultat d'analyse est considéré comme Réactif initial par le système informatique lorsque le résultat du test mis en oeuvre pour un marqueur donné est dans la zone des positifs.

Le logiciel doit constituer un fichier imprimable permettant d'associer pour chaque échantillon : le numéro de don, le type d'analyse, la date de l'analyse, le nom et le numéro de lot du réactif, la référence du distributeur et du lecteur utilisés, la valeur seuil, le résultat brut et le résultat net. Ce fichier sert au transfert des résultats et à leur archivage.
