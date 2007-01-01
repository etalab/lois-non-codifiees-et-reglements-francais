# Article Annexe

RÉSUMÉ STANDARDISÉ DE FACTURATION ANONYME

Le résumé standardisé de facturation anonyme (RSFA) est généré par un programme informatique (mentionné au I de l'article 6 du présent arrêté), à partir des factures établies à partir des bordereaux de facturation conformes au modèle fixé par voie réglementaire. Le format des fichiers comportant ces informations (dits résumés standardisés de facturation, RSF) et permettant la génération des RSFA, est disponible dans la documentation accompagnant le programme informatique mais aussi sur le site internet de l'agence technique de l'information sur l'hospitalisation (www.atih.sante.fr). Chaque résumé de facturation anonyme (RSF-A) comporte un numéro séquentiel, identique au numéro séquentiel de séjour des RHA correspondant, permettant ainsi d'apparier les RSF-A d'un séjour et les RHA du même séjour. Ce numéro séquentiel est déterminé pour chaque numéro de séjour SSR distinct, figurant sur les RHS comme les RSF.

Contenu du RSFA

Fichier de RSFA (*.rsfa)

Le RSFA est composé de sept catégories d'enregistrements correspondant aux différents groupes d'information du bordereau de facturation :

La catégorie A, début de facture :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (A) ;

- type de format RSF (1, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- sexe ;

- civilité ;

- nature opération ;

- nature assurance ;

- justification d'exonération du ticket modérateur ;

- code de prise en charge ;

- code grand régime ;

- total base de remboursement des prestations hospitalières ;

- total remboursable par l'assurance maladie obligatoire des prestations hospitalières ;

- total des honoraires facturés ;

- total des honoraires remboursables par l'assurance maladie ;

- total de la participation de l'assuré avant organismes complémentaires ;

- total remboursable organismes complémentaires pour les prestations hospitalières ;

- total remboursable organismes complémentaires pour les honoraires ;

- montant total facturé pour les prestations hospitalières.

La catégorie B, prestations hospitalières :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (B) ;

- type de format RSF (l, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- mode de traitement ;

- discipline de prestation (exemple discipline médico-tarifaire) ;

- justification d'exonération du ticket modérateur ;

- code acte ;

- quantité d'actes ;

- coefficient de l'acte ;

- code prise en charge du forfait journalier ;

- prix unitaire ;

- montant base de remboursement ;

- taux de remboursement ;

- montant remboursable par l'assurance maladie obligatoire ;

- montant total facturé ;

- montant remboursable par l'assurance maladie complémentaire ;

- montant remboursé NOEMIE retour ;

- nature opération récupération NOEMIE retour.

La catégorie I, prestation hospitalière, interruption de séjour :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (I) ;

- type de format RSF (I, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- nature d'interruption ou fin de séjour ;

- établissement.

La catégorie P, prestations hospitalières prothèses :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (P) ;

- type de format RSF (1, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- code LPP 1 ;

- quantité LPP1 ;

- tarif référence LPP/prix unitaire 1 ;

- montant facturé 1 ;

- code LPP 2 ;

- quantité LPP 2 ;

- tarif référence LPP/prix unitaire 2 ;

- montant facturé 2.

La catégorie H, prestations hospitalières médicaments :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (H) ;

- type de format RSF (1, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- code UCD ou CIP ;

- code taux ;

- prix d'achat ;

- montant écart indemnisable ;

- prix unitaire facturé ;

- quantité ;

- montant total facturé.

La catégorie C, honoraires :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (C) ;

- type de format RSF (1, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- mode de traitement ;

- discipline de prestation (exemple discipline médico-tarifaire) ;

- justification d'exonération du ticket modérateur ;

- code acte ;

- quantité d'actes ;

- coefficient de l'acte ;

- dénombrement ;

- prix unitaire ;

- montant base de remboursement ;

- taux de remboursement ;

- montant remboursable par l'assurance maladie obligatoire ;

- montant des honoraires, dépassement compris ;

- montant remboursable par l'assurance maladie complémentaire ;

- montant remboursé NOEMIE retour ;

- nature opération récupération NOEMIE retour.

La catégorie M, CCAM :

- numéro séquentiel (le même que pour les RHA) ;

- type d'enregistrement (M) ;

- type de format RSF (1, ancien, 2, nouveau) ;

- numéro séquentiel de facture ;

- numéro FINESS ;

- mode de traitement ;

- discipline de prestation (exemple discipline médico-tarifaire) ;

- code CCAM ;

- extension documentaire ;

- activité ;

- phase ;

- modificateur 1 ;

- modificateur 2 ;

- modificateur 3 ;

- modificateur 4 ;

- association non prévue ;

- code remboursement exceptionnel ;

- numéro dent 1 ;

- numéro dent 2 ;

- numéro dent 3 ;

- numéro dent 4 ;

- numéro dent 5 ;

- numéro dent 6 ;

- numéro dent 7 ;

- numéro dent 8 ;

- numéro dent 9 ;

- numéro dent 10 ;

- numéro dent 11 ;

- numéro dent 12 ;

- numéro dent 13 ;

- numéro dent 14 ;

- numéro dent 15 ;

- numéro dent 16.
