# Article 19

Informatique.

Les épreuves d'informatique à l'admissibilité se différencient comme suit :

- l'épreuve informatique I traite de problèmes d'algorithmique et de programmation. Elle porte principalement sur les parties A, B et C exposées ci-dessous ;

- l'épreuve informatique II traite essentiellement des fondements théoriques de l'informatique et se fonde sur les parties C, D et E.

On suppose de la part des candidats la connaissance d'un langage impératif (par exemple Pascal) et d'un langage fonctionnel (par exemple Lisp).

Le programme de mathématiques requis est celui des classes préparatoires scientifiques, filière MP.

A. - Architecture des machines et systèmes d'exploitation

1. Circuits logiques

Portes logiques, algèbre de Boole.

Circuits combinatoires : décodeurs, multiplexeurs, comparateurs. Circuits de calcul : décaleur, demi-additionneur, additionneur. Structure d'une unité arithmétique et logique.

Circuits à mémoire : bascules RS, bascule D. Structure d'une mémoire. Structure d'un ordinateur.

2. Microprogrammation

Architecture d'une micromachine, chemin des données, structure et exécution des micro-instructions, interprétation du langage machine.

3. Interruptions et entrées-sorties

Commutations de contexte, interruptions : niveaux et traitements.

Structure des bus, principe des entrées-sorties.

4. Processus

Etat d'un processus, représentation interne d'un processus par un bloc de contrôle.

Modèles de représentation des processus : graphes et automates finis.

Interactions de processus, problème du blocage : conditions nécessaires de blocage, méthodes de prévention, algorithme de détection, méthode d'évitement : algorithme du banquier.

Synchronisation de processus : problème de l'exclusion mutuelle, solutions logicielles.

Sémaphores, utilisation des sémaphores pour résoudre des problèmes classiques de synchronisation : le problème de l'exclusion mutuelle, le problème du producteur et du consommateur, le problème du lecteur et du rédacteur.

5. Gestion de la mémoire centrale

et ordonnancement de l'unité centrale

Principe de l'allocation contiguë, systèmes à partitions fixes ou variables.

Principe de l'allocation non contiguë, organisation matérielle des systèmes paginés et des systèmes segmentés, principaux algorithmes de pagination.

Ordonnanceurs, principaux algorithmes d'ordonnancement de l'unité centrale.

6. Gestion de la mémoire secondaire

Description des disques, algorithmes d'ordonnancement du disque.

Structure logique des fichiers, modes d'accès, allocation contiguë ou non contiguë, principales méthodes d'organisation des répertoires.

B. - Algorithmique et structures de données

1. Algorithmes

Notion d'algorithme, complexité d'un algorithme au sens du nombre d'opérations, exemples de calculs de complexité.

2. Structures de données classiques et algorithmes élémentaires

Listes, ensembles, arbres, graphes et leurs implantations.

Méthodes de parcours des arbres et des graphes : parcours en profondeur et en largeur.

Fermeture transitive, recherche des composantes connexes d'un graphe.

Arbres de recouvrement minimum d'un graphe, complexité.

3. Algorithmes de recherche

Recherche séquentielle, recherche dichotomique, arbres binaires de recherche : analyse du nombre de comparaisons.

Arbres AVL : adjonction et suppression, rééquilibrage.

Principe des méthodes de hachage, résolution des collisions par chaînage : chaînage séparé, hachage coalescent ; résolution des collisions par calcul : hachage linéaire et double hachage.

4. Algorithmes de tri

Tri par sélection, tri par insertion, tri rapide, tri par tas.

Complexité des algorithmes de tri : optimalité de la borne en O(n log2 n) pour les tris par comparaison.

C. - Théorie des langages et compilation

1. Langages

Structure de monoïde, monoïde libre, mots sur un alphabet, équations sur les mots.

Langages, systèmes de réécriture, grammaires et classification de Chomsky.

2. Langages rationnels

Expressions rationnelles et langages rationnels.

Automates finis et langages reconnaissables, lemme de l'étoile et théorème de Kleene.

Automates finis non déterministes, algorithme de déterminisation.

Algorithme de minimisation d'un automate fini.

Propriétés de fermeture de la famille des langages rationnels.

3. Langages algébriques

Grammaires algébriques (ou non contextuelles), arbres de dérivation, simplification des grammaires algébriques, forme normale de Greibach.

Automates à piles et langages algébriques, lemme d'itération.

Propriétés de fermeture de la famille des langages algébriques.

4. Analyse lexicale et analyse syntaxique

Rôle de l'analyse lexicale, spécification et reconnaissance des unités lexicales, utilisation d'automates finis déterministes pour l'analyse lexicale.

Rôle de l'analyse syntaxique, utilisation d'une grammaire pour l'analyse syntaxique.

Analyse descendante, analyse par descente récursive, grammaires LL(k).

Analyse ascendante, décalage et réduction, grammaires LR(k).

5. Compilation

Méthodes de traduction, contrôle de type, environnement d'exécution et production de code à partir de graphes acycliques.

D. - Calculabilité

1. Fonctions récursives, machines de Turing et lambda-calcul

Ensembles partiellement ordonnés, treillis, fonctions monotones, fonctions continues, opérateur de point fixe.

Machines de Turing déterministes et non déterministes, machines à registres, langages récursifs et récursivement énumérables.

Fonctions calculables par une machine de Turing, fonctions récursives et primitives récursives.

Lambda-calcul, bêta-conversion, théorème de Church-Rosser, représentation des fonctions récursives, équivalence avec le modèle des machines de Turing, théorèmes de point fixe.

2. Décidabilité

Langages et problèmes indécidables : exemple du problème de l'arrêt d'une machine de Turing. Techniques de réduction.

Propriétés de décidabilité des langages rationnels et algébriques.

3. NP-complétude

Problèmes polynomiaux, définition de la classe P.

Transformations polynomiales, problèmes polynomialement équivalents.

Complexité des machines de Turing non déterministes, définition de la classe NP.

Problèmes NP-complets, théorème de Cook, autres exemples de problèmes NP-complets.

E. - Sémantique et logique

1. Logique

Formules logiques, interprétation d'une formule, validité d'une formule, notion de modèle. Classification des formules logiques, calcul propositionnel et calcul des prédicats du premier ordre. Théorèmes de complétude, de compacité et de finitude.

Formes normales prénexe, conjonctive et disjonctive, théorème de Herbrand.

Déduction naturelle, méthode de résolution et algorithme d'unification.

Eléments de programmation logique.

2. Sémantique

Description sémantique des programmes : sémantique dénotationnelle.

Interprétation des programmes par plus petit point fixe, théorème du point fixe de Knaster-Tarski.

3. Vérification de programmes

Logique de Hoare et preuves de programmes par assertions. Transformations de programme et preuves de correction.
