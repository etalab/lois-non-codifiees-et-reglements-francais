# Article ANNEXE

7. Règles supplémentaires pour les services de télévision et de

radiodiffusion sonore ayant au moins une composante embrouillée

7.1. Embrouillage

Les composantes image et sons des services de télévision et de radiodiffusion sonore peuvent être embrouillées conformément à la partie 6 de la spécification (réf. 1), en particulier à des fins d'accès conditionnel. L'embrouillage de tout ensemble de composantes d'un même service susceptibles d'être reçues simultanément doit être contrôlé par, au plus, deux séries de mots de contrôle indépendantes.

Par exemple, pour un service TV à quatre composantes : image, son principal, sons additionnels 1 et 2, les possibilités suivantes sont autorisées :

Les quatre composantes embrouillées avec la série de mots de contrôle MC1 ;

L'image embrouillée avec la série de mots de contrôle MC1, le son principal et les sons additionnels 1 et 2 embrouillés avec la série MC2 ;

L'image et le son principal embrouillés avec la série de mots de contrôle MC1, le son additionnel 1 embrouillé avec la série MC2 et le son additionnel 2 embrouillé avec la série MC3.

Les combinaisons suivantes sont interdites :

L'image embrouillée avec la série de mots de contrôle MC1, le son principal avec la série MC2 et au moins l'un des sons additionnels 1 ou 2 embrouillé avec la série MC3.

7.2. Système d'accès conditionnel

Lorsque l'embrouillage est utilisé à des fins d'accès conditionnel, le système d'accès conditionnel mis en oeuvre est le système provisoirement dénommé Eurocrypt (réf. 2), identifié par la valeur hexadécimale 40 du code CA de la voie d'identification des services.

Les opérateurs des services à accès conditionnel pourront être amenés à utiliser plusieurs types d'algorithmes de chiffrement différents (signalés par la valeur du code CI des messages d'accès conditionnel) au cours de la vie du système. Un type d'algorithme pouvant être utilisé est celui qui est implanté dans la carte à mémoire PC2 (identifié par la valeur hexadécimale 20 du code CI), dont la description externe est annexée à la spécification provisoirement dénommée Eurocrypt.

Les titres d'accès aux services et les désembrouilleurs ou décodeurs désembrouilleurs pourront être commercialisés ou distribués indépendamment les uns des autres.

7.3. Messagerie d'accès conditionnel

Lorsqu'une messagerie d'accès conditionnel est mise en oeuvre, la longueur de tous les messages d'accès conditionnel à format variable décrits dans la spécification provisoirement dénommée Eurocrypt (ECM, EMM-G, C et U) est limitée à une valeur telle qu'ils soient contenus dans deux paquets au maximum.

Dans une adresse ECM ou EMM donnée, les messages d'accès conditionnel correspondent tous au même type d'algorithme (identifié par une valeur du code C.I.).

Dans un canal, les messages de gestion des accès sont regroupés dans un service d'adressage sur antenne unique.

Le paramètre PI = A4 (adresse unique de l'usager UA) ne sera pas utilisé dans les messages de gestion des titres d'accès individualisés (EMM-U) radiodiffusés.

Réf. 1 : NF C 90-001 et addendum 1 : spécification du système D2-Mac/Paquet.

Réf. 2 : Système d'accès conditionnel pour la famille Mac/Paquet :

Eurocrypt.
