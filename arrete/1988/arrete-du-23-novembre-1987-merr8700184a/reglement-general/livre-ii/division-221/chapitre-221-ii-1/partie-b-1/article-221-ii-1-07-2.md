# Article 221-II-1/07-2

Calcul du facteur "si"

1 Le facteur si doit être calculé pour chaque cas d'envahissement hypothétique d'un compartiment ou groupe de compartiments, compte tenu des indications ci-après et des dispositions du présent article :

θe est l'angle d'inclinaison correspondant à la position d'équilibre, quel que soit le stade de l'envahissement, en degrés ;

θv est, quel que soit le stade de l'envahissement, l'angle auquel le bras de levier de redressement devient négatif, ou l'angle auquel une ouverture qui ne peut pas être fermée de manière à être étanche aux intempéries est immergée ;

GZmax est le bras de levier de redressement positif maximal, en mètres, jusqu'à l'angle θv ;

Arc est l'arc des bras de levier de redressement positifs, en degrés, mesuré à partir de l'angle θe. L'arc positif doit être pris jusqu'à l'angle θv ;

Stade de l'envahissement est toute étape discrète du processus d'envahissement, y compris le stade qui précède l'équilibrage (s'il y en a un) jusqu'à ce que la position finale d'équilibre ait été atteinte.

1.1 Le facteur sj, pour tout cas d'avarie, quelles que soient les conditions de chargement initiales di, est calculé à l'aide de la formule suivante :

si = minimum { s intermédiaire,i ou s final,i . s mom,i}

dans laquelle,

s intermédiaire,i est la probabilité de survivre à tous les stades intermédiaires de l'envahissement jusqu'à la position d'équilibre finale et est calculée de la manière indiquée au paragraphe 2 ;

s final,i est la probabilité de survivre en position d'équilibre finale après l'envahissement. Elle est calculée de la manière indiquée au paragraphe 3 ;

s mom,i est la probabilité de survivre aux moments d'inclinaison et est calculée de la manière indiquée au paragraphe 4.

2 Le facteur s intermédiaire,i est applicable uniquement aux navires à passagers (pour les navires de charge, s intermédiaire,i devrait être pris comme égal à l'unité) et doit être pris comme étant le plus petit des facteurs s obtenus à tous les stades de l'envahissement, y compris le stade précédant l'équilibrage, s'il y en a un, et est calculé comme suit :

s intermédiaire,i = [Gzmax/0,05.Arc/7]1/4

Dans cette formule, la valeur GZmax ne doit pas être supérieur à 0,05 mètre et Arc ne doit pas être supérieur à 7°. Si l'angle d'inclinaison intermédiaire est supérieur à 15°, s intermédiaire est égal à 0. Lorsque des dispositifs d'équilibrage sont nécessaires, la durée de l'équilibrage ne doit pas être supérieure à 10 minutes.

3 On obtient le facteur s final,i à l'aide de la formule suivante :

s final,i = K [Gzmax/0,012.Arc/16]1/4

dans laquelle,

GZmax ne doit pas être supérieur à 0,12 mètre ;

Arc ne doit pas être supérieur à 16° ;

K = 1 si θe ≤ θmin

K = 0 si θe ≥ θmax

K = √ θmax - θe/θmax - θmin dans les autres cas,

dans cette formule :

θmin est égal à 7° pour les navires à passagers et à 25° pour les navires de charge ; et

θmax est égal à 15° pour les navires à passagers et à 30° pour les navires de charge.

4 Le facteur s mom,i est applicable uniquement aux navires à passagers (pour les navires de charge, s mom,i doit être pris comme égal à l'unité) et est calculé à la position d'équilibre finale à l'aide de la formule suivante :

s mom,I = (Gzmax - 0,04).Déplacement/Mincl.

dans laquelle,

Déplacement est le déplacement à l'état intact au tirant d'eau de compartimentage ;

Mincl. est le moment d'inclinaison maximal hypothétique, calculé de la manière indiquée au paragraphe 4.1 ; et

s mom,i ≤ 1

4.1 Le moment d'inclinaison Mincl. doit être calculé comme suit :

Mincl. = maximum {Mpassagers ou Mvent ou Memb+radeaux de sauvetage}

4.1.1 Mpassagers est le moment d'inclinaison maximal hypothétique dû au rassemblement des passagers et doit être calculé comme suit :

Mpassagers = (0,075.Np).(0,45.B) (tm)

Dans cette formule :

Np est le nombre maximal de passagers que le navire est autorisé à transporter dans les conditions d'exploitation correspondant au tirant d'eau maximal de compartimentage considéré ; et

B est la largeur du navire.

A titre de variante, le moment d'inclinaison peut être calculé en prenant pour hypothèse que les passagers sont répartis à raison de 4 personnes par mètre carré de surface de pont disponible sur un bord du navire, sur les ponts où se trouvent les postes de rassemblement, et de manière à produire le moment d'inclinaison le plus défavorable. On prend aussi pour hypothèse un poids de 75 kg par passager.

4.1.2 Mvent est la force maximale hypothétique du vent qui s'exerce en situation d'avarie :

Mvent = (P.A.Z)/9806 (tm)

Dans cette formule :

P = 120 N/m2

A = aire latérale projetée au-dessus de la flottaison

Z = distance entre le centre de l'aire latérale projetée au-dessus de la flottaison et T/2 ; et

T = tirant d'eau du navire di.

4.1.3 Memb+radeaux de sauvetage est le moment d'inclinaison maximal hypothétique dû à la mise à l'eau de toutes les embarcations et de tous les radeaux de sauvetage sous bossoirs sur un bord du navire avec leur plein chargement. Pour le calculer, on part des hypothèses suivantes :

.1 on suppose que toutes les embarcations de sauvetage et tous les canots de secours installés sur le bord du côté duquel le navire s'est incliné après avoir subi une avarie sont débordés avec leur plein chargement et sont prêts à être mis à la mer ;

.2 pour les embarcations de sauvetage qui sont conçues pour être mises à l'eau avec leur plein chargement depuis la position d'arrimage, on prend le moment d'inclinaison maximal au cours de la mise à l'eau ;

.3 on suppose qu'un radeau de sauvetage avec son plein chargement est attaché à chaque bossoir sur le bord du côté duquel le navire s'est incliné après avoir subi l'avarie et qu'il est débordé, prêt à être mis à la mer ;

.4 les personnes qui ne se trouvent pas dans les engins de sauvetage débordés ne contribuent pas à augmenter le moment d'inclinaison ou le moment de redressement ; et

.5 on suppose que les engins de sauvetage sur le bord du navire opposé à celui du côté duquel le navire s'est incliné se trouvent en position d'arrimage.

5 L'envahissement asymétrique doit être réduit au minimum grâce à des dispositions efficaces. Lorsqu'il est nécessaire de corriger de grands angles de gîte, les moyens adoptés pour l'équilibrage doivent, si possible, être automatiques, mais dans tous les cas où des commandes des dispositifs d'équilibrage sont prévues, leur manœuvre doit pouvoir se faire d'un point situé au-dessus du pont de cloisonnement. Ces dispositifs, ainsi que leurs commandes, doivent être jugés acceptables par l'Administration(*). Le capitaine du navire doit être en possession des renseignements nécessaires concernant l'utilisation des dispositifs d'équilibrage.

On doit disposer de moyens de sondage efficaces, accessibles du pont de cloisonnement, afin de vérifier le niveau du liquide dans les compartiments desservis.

Lorsque des traverses d'équilibrage sont prévues, elles doivent, en principe, rester dans le compartiment principal ou se trouvent les compartiments étanches qu'elles desservent.

La durée d'équilibrage est calculée entre l'angle de gîte avant équilibrage et l'angle de gîte tel que acceptable.

5.1 Les citernes et les compartiments servant à un tel équilibrage doivent être munis de conduits d'aération ou de moyens équivalents d'une section suffisante pour que le flux d'eau dans les compartiments d'équilibrage ne soit pas retardé.

5.2 Le facteur si doit toujours être pris égal à zéro dans les cas où la flottaison finale, compte tenu de l'enfoncement, de l'inclinaison et de l'assiette, immerge :

.1 le bord inférieur des ouvertures par lesquelles un envahissement progressif peut se produire, cet envahissement n'étant pas pris en considération dans le calcul du facteur si. Ces ouvertures incluent les conduits d'aération, les manches de ventilation et les ouvertures fermées au moyen de portes ou de panneaux d'écoutille étanches aux intempéries ; et

.2 une partie quelconque du pont de cloisonnement des navires à passagers considérée comme un itinéraire d'évacuation horizontal aux fins de satisfaire aux dispositions du chapitre 221-II-2.

5.3 Le facteur si doit être pris égal à zéro si, compte tenu de l'enfoncement, de l'inclinaison et de l'assiette, l'une quelconque des situations ci-après se produit à un stade intermédiaire ou au stade final de l'envahissement :

.1 immersion d'une ouverture servant d'échappée verticale ménagée dans le pont de cloisonnement aux fins de satisfaire aux dispositions du chapitre 221-II-2 ;

.2 les commandes destinées à actionner les portes étanches à l'eau, les dispositifs d'équilibrage, les soupapes de tuyautages ou de conduits de ventilation qui sont censés assurer le maintien de l'intégrité des cloisons étanches à l'eau depuis un emplacement situé au-dessus du pont de cloisonnement deviennent inaccessibles ou inutilisables ;

.3 immersion d'une partie des tuyautages ou des conduits de ventilation traversant un cloisonnement étanche à l'eau qui est située dans un compartiment pris en considération dans les cas d'avarie contribuant à l'indice obtenu A, si elle n'est pas munie de moyens de fermeture étanches à l'eau au niveau de chaque cloisonnement.

5.4 Toutefois, si les compartiments supposés envahis du fait d'un envahissement progressif sont pris en considération dans les calculs de stabilité après avarie, on peut calculer plusieurs valeurs de s intermédiaire,i en prenant pour hypothèse un équilibrage à d'autres stades supplémentaires de l'envahissement.

5.5 Sauf dans le cas prévu au paragraphe 5.3.1, les ouvertures fermées par des couvercles de trou d'homme et des bouchons à plat pont étanches à l'eau, les petits panneaux d'écoutille étanches à l'eau, les portes à glissières étanches à l'eau commandées à distance, les hublots de type fixe, ainsi que les portes d'accès et panneaux d'écoutille étanches à l'eau qui doivent rester fermés en mer, n'ont pas besoin d'être pris en considération.

6 En cas de cloisonnements horizontaux étanches à l'eau au-dessus de la flottaison considérée, on obtient la valeur s calculée pour le compartiment ou groupe de compartiments inférieur en multipliant la valeur obtenue conformément au paragraphe 1.1 par le facteur de réduction vm calculé conformément au paragraphe 6.1, ce facteur représentant la probabilité selon laquelle les espaces situés au-dessus du compartimentage horizontal ne seront pas envahis.

6.1 Le facteur vm est calculé à l'aide de la formule suivante :

vm = v(Hj, n, m, d) - v(Hj, n, m-1, d))

dans laquelle :

Hj, n, m est la hauteur la plus faible au-dessus du tracé de la quille, en mètres, comprise dans une fourchette longitudinale allant de x1(j)...à x2(j+n-1) du mième cloisonnement horizontal qui est supposé limiter l'étendue verticale de l'envahissement pour les compartiments touchés considérés ;

Hj, n, m-1 est la hauteur la plus faible au-dessus du tracé de la quille, en mètres, comprise dans une fourchette longitudinale allant de x1(j)...à x2(j+n-1) du mième cloisonnement horizontal qui est supposé limiter l'étendue verticale de l'envahissement pour les compartiments touchés considérés ;

j est l'extrémité arrière des compartiments touchés considérés ;

m représente chaque cloisonnement horizontal compté verticalement à partir de la flottaison considérée ;

d est le tirant d'eau en question tel que défini à l'article 221-II-1/02 ; et

x1 et x2 représentent les extrémités du compartiment ou groupe de compartiments considéré à l'article 221-II-1/07-1.

6.1.1 On obtient les facteurs v(Hj,n,m, d) et v(Hj,n,m-l, d) à l'aide des formules suivantes :

v (H, d) = 0,8 (H-d)/7,8 si (Hm-d) est inférieur ou égal à 7,8 mètres ;

v( H, d) = 0,8 + 0,2 [(H-d) - 7,8/4,7] dans tous les autres cas,

dans lesquelles :

v(Hj, n, m, d) doit être pris égal à 1 si Hm coïncide avec le cloisonnement étanche à l'eau le plus élevé du navire dans la fourchette (x1(j)...x2(j+n-1)), et

v(Hj, n, 0, d) doit être pris égal à 0.

En aucun cas le facteur vm ne doit être inférieur à 0 ni supérieur à 1.

6.2 En général, on obtient chaque contribution dA à l'indice A dans le cas de compartimentages horizontaux à l'aide de la formule suivante :

dA=pi.[v1.smin1+ (v2-v1).smin2 + ...+(1-vm-1).sminm]

dans laquelle :

vm = la valeur de v calculée conformément au paragraphe 6.1 ;

smin = la valeur la plus faible du facteur s pour toutes les combinaisons d'avarie obtenue lorsque l'avarie hypothétique s'étend vers le bas à partir de la hauteur d'avarie hypothétique Hm.

(*) Se reporter à la Recommandation sur une méthode normalisée permettant de satisfaire aux prescriptions relatives aux traverses d'équilibrage à bord des navires à passagers, que l'Organisation a adoptée par la résolution A.266(VIII), telle qu'amendée par la résolution MSC.245(83).
