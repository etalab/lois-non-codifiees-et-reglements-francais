# Article Annexe 8

**MODULE DE RÉPARTITION DES CONSOMMATIONS PAR LOGEMENT D'UN IMMEUBLE COLLECTIF EN CAS DE CHAUFFAGE INDIVIDUEL OU INDIVIDUEL CENTRALISÉ**

**8.1. Chauffage**

Les consommations de la synthèse d'étude thermique sont réparties à l'appartement sur la base d'une répartition simplifiée des déperditions par l'enveloppe et le renouvellement d'air comme suit.

Les déperditions par l'enveloppe de l'appartement i, D<sub>env</sub>(i), sont évaluées par la formule :

D<sub>env</sub>(i) = 1.8*A<sub>baiesNord</sub>(i) + 0.9*A<sub>baiesEstOuest</sub>(i) + 0*A<sub>baiesSud</sub>(i) + 0.3*A<sub>plancherhaut</sub>(i) + 0.6*A<sub>paroiesverticales</sub>(i) + 0.15*A<sub>plancherbas</sub>(i)

Avec :

- A<sub>baiesNord</sub>(i), la surface de baies orientées au nord de l'appartement i (en m²) ;

- A<sub>baiesEstOuest</sub>(i), la somme des surfaces de baies orientées à l'est et à l'ouest de l'appartement i (en m²) ;

- A<sub>baiesSud</sub>(i), la surface de baies orientées au sud de l'appartement i (en m²) ;

- A<sub>plancherhaut</sub>(i), la surface de plancher haut de l'appartement i, donnant sur l'extérieur ou un local non chauffé (en m²) ;

- A<sub>paroiesverticales</sub>(i), la surface de parois verticales opaques de l'appartement i, donnant sur l'extérieur ou un local non chauffé (en m²) ;

- A<sub>plancherbas</sub>(i), la surface de plancher bas de l'appartement i, donnant sur l'extérieur ou un local non chauffé (en m²).

Les déperditions par renouvellement d'air de l'appartement i, D<sub>vent</sub>(i), sont évaluées par :

D<sub>vent</sub>(i) = 0.34 * A<sub>habitable</sub>(i)

Avec A<sub>habitable</sub>(i), la surface habitable de l'appartement i (en m²).

Les déperditions totales de l'appartement i, D<sub>tot</sub>(i), sont données par :

D<sub>tot</sub>(i) = D<sub>env</sub>(i) + D<sub>vent</sub>(i)

La clé de répartition chauffage pour un appartement i, Clé<sub>ch</sub>(i), a donc pour valeur :

Clé<sub>ch</sub>(i) = D<sub>tot</sub>(i) / D<sub>totbat</sub>

Avec D<sub>totbat</sub> = Σ D<sub>tot</sub> (i), somme des déperditions de tous les appartements du bâtiment.

Si des logements ont des sources d'énergie de chauffage différentes, la clé de répartition est calculée par type d'énergie.

Cette clé de répartition s'applique à la consommation de chauffage par mètre carré de surface habitable du bâtiment, calculée selon les règles Th-C-E.

**8.2. Eau chaude sanitaire**

La clé de répartition est calculée en fonction des besoins d'ECS de l'appartement, calculés selon les règles Th-CE de la RT 2005.

Le besoin en eau chaude sanitaire de l'appartement i, B<sub>ecs</sub>(i) est calculé comme suit :

- si A<sub>habitable</sub>(i) < 27 m² : B<sub>ecs</sub>(i) = 470.9*ln (A<sub>habitable</sub>(i)) - 1075) (en kWh), (1)

- B<sub>ecs</sub>(i) = 17.7*A<sub>habitable</sub>(i) (en kWh) sinon.

La clé de répartition des besoins d'eau chaude sanitaire pour un appartement i, Clé<sub>ecs</sub>(i), est donnée par :

Clé<sub>ecs</sub>(i) = B<sub>ecs</sub>(i) / B<sub>ecsbat</sub>

Avec B<sub>ecsbat</sub> = Σ B<sub>ecs</sub>(i), somme des besoins d'ECS de tous les appartements du bâtiment.

Si des logements ont des sources d'énergie différentes pour la production d'ECS, la clé de répartition est calculée par type d'énergie.

Cette clé de répartition s'applique à la consommation d'eau chaude sanitaire par mètre carré de surface habitable du bâtiment, calculée selon les règles Th-C-E.

**8.3. Refroidissement**

Les consommations de refroidissement par mètre carré de surface habitable seront prises égales à celles de la partie refroidie du bâtiment.
