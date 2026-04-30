---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.9"
ordre_document: 34
titre: "Planning chemin de fer (génie civil)"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 34 Planning chemin de fer (génie civil)
resume_section: |-
  ### Résumé : 4.9 Planning chemin de fer (génie civil)
  
  #### **Principe de la méthode**
  Le planning spatio-temporel est utilisé pour des projets linéaires (routes, voies ferrées, pipelines, etc.) ou répétitifs (bâtiments). Il permet d’optimiser les rotations d’engins (terrassement, bétonnage) et la gestion de production en préfabrication.
  
  #### **Cycle de travail des camions de terrassement**
  Le cycle inclut : chargement, transport en charge, déchargement, retour à vide. La durée d’un cycle est mesurée par chronométrage et dépend de facteurs comme le rendement de la pelle, l’efficience, le facteur de remplissage, la capacité des camions, la distance et les conditions de trafic.
  
  - **Temps de chargement** : dépend du rendement de la pelle, de son efficience, du facteur de remplissage et de la capacité du camion.
  - **Temps de transport** : calculé selon la vitesse (en charge/à vide), la distance et le trafic.
  - **Temps de déchargement** : mesuré sur site ou simulé.
  
  #### **Optimisation des rotations**
  - **Nombre optimal de camions** : rapport entre la durée du cycle et le temps de chargement.
  - **Durée des travaux** : fonction du volume de terre, du cycle et du nombre de camions.
  
  #### **Planning des opérations de préfabrication et pose**
  Optimisation des étapes de fabrication, stockage et pose des éléments préfabriqués :
  - **Courbe de pose** : basée sur la cadence de pose (éléments/jour).
  - **Courbe de fabrication** : dépend de la cadence de fabrication et des délais de séchage.
  - **Courbe de stocks** : calculée selon les cadences et les délais de stockage.
  
  #### **Études de cas**
  1. **Terrassement** : calcul du cycle des camions, du nombre optimal de camions (5 ou 6) et de la durée des travaux.
  2. **Préfabrication de corniches** : analyse des cadences (fabrication/pose) et des stocks pour 200 unités, avec trois scénarios (cadences de pose : 2, 4 ou 5 unités/jour).
  
  Les figures et tableaux illustrent les calculs et les courbes pour chaque cas.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[33-application-4-5|Application 4-5]]"
section_suivante: "[[35-application-4-6|Application 4-6]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["34_4.9_planning_chemin_de_fer_génie_civil.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.9 Planning chemin de fer (génie civil)

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0170-00.png]]

_**Figure 4.52 Diagramme GANTT de l’application 4-5, élaboré avec MS Project**_

**Principe de la méthode** 

Ce planning est une représentation spatio-temporelle qui intègre l’emplacement des tâches dans le temps. Il est surtout utilisé pour planifier des projets s’effectuant le long d’un linéaire comme les routes, autoroutes, voies ferrées, pipelines, tunnels ou des travaux répétitifs par étages ou zones dans des bâtiments élevés. 

On peut aussi utiliser ce type de planning pour étudier les rotations de camions notamment dans les travaux de terrassements ou dans les opérations de bétonnage et le planning de la gestion de production dans la préfabrication. La planification présentée dans ce chapitre se destine au génie civil. 

La planification globale d’un projet de construction en chemin de fer sera présentée au chapitre 6, qui traite de la planification en Lean Construction. 

**Planning de rotation des engins de terrassement** 

**Étude d’un cycle de travail** 

L’étude du planning de rotation des camions de terrassement a pour objectif d’optimiser l’utilisation du matériel. Le cycle de rotation des camions est composé de plusieurs étapes qui ont chacune une durée élémentaire bien définie. De fait, un camion effectue les mêmes tâches de façon cyclique : le chargement, le transport en charge, le déchargement et le retour à vide. 

La durée d’un cycle de travail représente le temps nécessaire pour exécuter un tour complet et revenir au point de départ. 

Pour déterminer la durée d’un cycle des camions, il suffit d’utiliser un chronomètre et de mesurer le temps de chaque opération. La durée retenue est une moyenne sur quelques cycles de rotations. 

La **fgure 4.53** schématise un cycle entier ainsi que les paramètres qui influent sur le temps de chaque activité du cycle de travail.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0172-00.png]]

_**Figure 4.53 Paramètres et composantes d’un cycle de terrassement**_ 

**Temps de chargement « Tch »** 

Le temps de chargement, exprimé en minute, correspond au temps qu’il faut pour remplir le camion de transport de terre. Ce temps dépend de plusieurs facteurs tels que : le rendement de la pelle qui fait le chargement, l’efficience, le facteur de remplissage et la capacité du camion de chargement et de transport. Il est déterminé par la formule suivante :

Tch=Capacité du camionRth×K×Fr Rendement théorique de la pelle « Rth » : il est exprimé en m[3] / h et dépend du volume du godet en m[3] et du temps mis par la pelle pour effectuer un cycle de chargement du godet. Efficience « K » : c’est le temps de travail effectif de la pelle en une heure. L’efficience est représentée par un coefficient exprimé en %, déterminé en effectuant le rapport entre le temps de travail effectif de la pelle et une heure écoulée. Facteur de remplissage « Fr » : lorsque le sol à déplacer est composé de petits débris rocheux, une pelle ne sera pas totalement remplie. Le facteur de remplissage représente le pourcentage du volume de godet effectivement rempli. Capacité du camion : c’est le volume de terre que peut contenir la benne d’un camion ou la masse de terre qu’il peut transporter. La capacité du camion est égale à la charge utile (tonne) divisée par la masse volumique apparente du déblai. 

**Durée de transport en charge et à vide** 

La durée de transport en charge ou à vide dépend de la vitesse de circulation, du trafic routier et du trajet à parcourir par les camions entre les zones de chargement et de déchargement : 

Vitesses de transport des camions : elles correspondent aux vitesses maximales du camion en charge et à vide. Distance à parcourir : c’est le trajet à faire entre les deux sites, chantier et décharge. Elle est évaluée au moyen d’une carte ou par mesure sur le terrain à l’aide d’un compteur kilométrique. Conditions du trafic routier : elles permettent d’évaluer la vitesse moyenne que le camion pourra atteindre sur une distance à parcourir. Leur évaluation nécessite d’observer ou de connaître l’état du trafic sur le trajet à parcourir. Temps de transport : ils s’obtiennent directement en mesurant le temps par un chronomètre ou en assemblant la collecte des informations précédentes. 

**Durée de déchargement** 

La durée de déchargement dépend des conditions sur site. Le temps de déchargement est évalué directement par l’observation ou déterminé par une simulation chronométrée.

La **fgure 4.54** présente, sous forme de courbe, les quatre activités qui composent le cycle des camions de terrassement en déblai. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0174-02.png]]

_**Figure 4.54 Schéma d’un cycle de camion**_ 

**Détermination du nombre optimal de camions et de la durée des travaux** 

Le nombre optimal des camions dépend du temps de chargement et de la durée du cycle d’un camion. Cependant, la durée des travaux est fonction de la quantité des terres à déplacer, de la durée d’un cycle et du nombre de camions à utiliser : 

Nombre optimal des camions « N » : le nombre optimal de camions est égal au rapport du temps du cycle de camion sur le temps de chargement, arrondi par excès ou par défaut : 

N=Durée d’un cycleTemps de chargement 

Temps de rotation : c’est le temps mis par le premier camion entre le moment où il se présente devant le chargeur pour être chargé et le moment où il s’y présentera après avoir effectué un cycle complet. Nombre de rotations des camions « Nr » : pour déterminer le nombre de rotations des camions, il faut tenir compte du

changement du volume des terres à la suite de l’opération d’excavation et du phénomène de tassement (voir **fg. 4.55** ) : 

Nr=Volume des terres foisonnées VTCapacité des convois tous les camions 

Avec : 

Volume transporté : VT = V0 × f Volume du remblai : VR = V0 × f′ Volume du déblai : V0 Coefficient foisonnement initial : f (peu après l’excavation) Coefficient foisonnement initial : f′ (après tassement naturel) 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0175-04.png]]

_**Figure 4.55 Schématisation du phénomène de foisonnement des sols**_ 

Détermination de la durée de chantier : la durée de chantier de terrassement est le produit de la valeur de l’entier supérieur le plus proche de Nr et le temps de rotation des camions : 

Durée=Nr×Temps de rotation du camion 

**Exemple d’étude de rotation des camions de terrassement** 

**Énoncé** 

On se propose d’étudier le planning chemin de fer des travaux de terrassement en déblai d’un chantier qui a les caractéristiques suivantes : 

L’entreprise dispose d’une pelle hydraulique ayant un rendement théorique de 120 m[3] /h et travaille effectivement 50 minutes par heure. Le remplissage du godet se fait à 85 %. La capacité des camions de transport des déblais est de 15 m[3] .

La décharge se situe à 8 km du chantier. Conditions du trafic routier : la traversée d’un centre-ville est difficile, la vitesse moyenne des camions est de 10 km/h sur 3 km et elle est maximale sur le reste du parcours (5 km). Les vitesses maximales sont en charge de 30 km/h et à vide 50 km/h. 

L’observation du site de déchargement permet d’estimer le 

temps de déchargement d’un camion à 5 min.

- Temps de chargement « Tch » : 

On demande de : 

1. Déterminer le cycle de travail des camions de terrassement. 

2. Déterminer le nombre nécessaire de camions et la durée des travaux. 

**Solution** 

1. Détermination du cycle de travail des camions de terrassement 

Le rendement théorique de la pelle « Rth » est de 120 m[3] /h, cela signifie qu’elle est capable de charger 120 m[3] de terre en une heure. 

Efficience « K » : la pelle travaille effectivement 50 minutes pour 60 minutes écoulées : K est égale à 50/60 = 0,83 ou 83 %. 

Le rendement réel de la pelle baisse en réalité par l’efficience à 120 × 83 %  = 99,6 m[3] /h. 

Le facteur de remplissage est de 85 %, le rendement de la pelle de 99,6 m[3] /h baisse alors en déplaçant des débris rocheux à 99,6 × 85 % = 84,66 m[3] /h. La pelle possède donc dans ces conditions un rendement réel de 84,66 m[3] /h. 

Le camion peut transporter dans sa benne 15 m[3] de terre. 

Temps de chargement : pour remplir un camion de 15 m[3] , avec une pelle chargeant 84,66 m[3] en une heure (60 min), il faudra un temps de : 1584,66×60 = 10,63 min. On peut calculer directement ce temps par la formule suivante :

- Temps de transport : Distance à parcourir : la décharge se situe à 8 km du chantier. Temps de transport : sur les 3 km de traversée du centreville, le camion roule à 10 km/h en charge et 20 km/h à vide. Il lui faut donc 3 × 60/10 = 18 minutes (en charge) et 3 × 60/20 = 9 minutes (à vide) pour le traverser. Sur le reste du parcours, il lui faut en charge : 5 × 60/30 = 10 min, et à vide : 5 × 60/50 = 6 min. D’où le temps total de transport : → En charge : 18 + 10 = 28 min. → À vide : 9 + 6  = 15 min.

- Temps de déchargement d’un camion : 5 min.

- Durée de cycle de camion 

Elle est égale à la somme des temps de chargement, de transport en charge et à vide (aller et retour) et de déchargement (voir **tab. 4.22** ). Le schéma d’un cycle de camion est présenté dans la **fgure 4.56** . Dans notre cas étudié, le temps d’un cycle est égal à 58,63 minutes 

_**Tableau 4.22 Durée d’un cycle de camion**_ 

|**Composante du cycle**|**Temps (min)**|
|---|---|
|_Chargement_<br>_Transport en charge_<br>_Déchargement_<br>_Transport à vide_|_10,63_<br>_28_<br>_5_<br>_15_|
|_Total_|_58,63 min_|

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0178-00.png]]

_**Figure 4.56 Schéma de la détermination d’un cycle de camion**_ 

2. Détermination du nombre nécessaire de camions et de la durée des travaux 

Le nombre optimal de camion pour un chantier de terrassement ayant une durée de cycle de 58,63 minutes et une durée de chargement de 10,63 minutes est : 

- 1[er] cas : cas de 5 camions : on prend l’entier immédiatement inférieur à la valeur trouvée : 5 camions (voir **fg. 4.57** ). On choisit dans ce cas de faire travailler les camions à 100 %, et la pelle hydraulique va attendre un temps de : 58,63 – 5 × 10,63 = 5,23 min. 

- 2[e] cas : cas de 6 camions : on prend l’entier immédiatement 

- supérieur à la valeur trouvée : 6 camions (voir **fg. 4.58** ). Dans ce cas, on choisit de faire travailler la pelle hydraulique à 100 %, ce sont donc les camions qui attendent d’une durée égale à : 6 × 10,63 – 58,63 = 5,15 min.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0179-00.png]]

_**Figure 4.57 Schéma du planning chemin de fer des travaux de terrassement (1[er] cas)**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0180-00.png]]

_**Figure 4.58 Schéma du planning chemin de fer des travaux de terrassement (2[e] cas)**_ 

**Planning des opérations de fabrication, stockage et pose** 

Ce planning a pour but d’optimiser le déroulement des opérations de fabrication, de pose et de stockage des éléments préfabriqués en usine ou sur chantier. Pour élaborer ce planning, on trace les courbes de pose, de fabrication et de stockage dans un système d’axes formé avec le temps en abscisses et le nombre d’unités à poser en ordonnées.

Les dates de début et de fin de pose sont définies par le planning travaux. La cadence de pose représente le nombre d’éléments mis en place par jour : 

Cadence de pose=Nombre d’élément à poser Nombre de jour 

**Courbe de fabrication** 

Elle est tracée sur la base de la durée de préfabrication déterminée par la formule suivante : 

Durée de fabrication=Quantité à fabriquerCadence de fabrication 

Deux cas se présentent : soit la cadence de fabrication est inférieure à la cadence de pose, soit la cadence de fabrication est supérieure ou égale à la cadence de pose. 

**1[er] cas : la cadence de fabrication est inférieure à la cadence de** 

**pose** 

On cherche la date de fin de fabrication puis on en déduit la date de début de fabrication. 

→ Fin de fabrication = fin de pose – durée de pose – durée de séchage 

→ Début de fabrication = fin de fabrication + 1 – durée de fabrication 

**2[e] cas : la cadence de fabrication est supérieure ou égale à la cadence de pose** 

On cherche la date de début de fabrication puis on en déduit la date de la fin de fabrication. 

→ Début de fabrication = début de pose – délai de séchage – durée de pose 

→ Fin de fabrication = début de fabrication – 1 + durée fabrication 

**Courbe de stocks** 

Le stockage des éléments préfabriqués dépend de la durée de séchage et de démoulage qui varie généralement entre 12 et 36 h :

Début de stock = début de fabrication + délai de séchage 

La courbe de stocks se décompose en trois parties S1, S2 et S3 suivantes : 

- **Stock [S1]** (début de la pose) : **[S1]** = (début de pose – début de stock) × cadence de fabrication 

- **Stock [S2]** (fin de la fabrication) : **[S2]** = S1 – (fin de fabrication + 1 – début de pose) × (cadence pose – cadence fabrication) 

- **Stock [S3]** (fin de la fabrication + 1 jour) : **[S3]** = S2 + (cadence de fabrication – cadence de pose) 

**Étude de cas des éléments préfabriqués** 

On veut étudier la planification des travaux de préfabrication et de pose de 200 corniches préfabriquées pour un pont. 

**Données** 

Nombre de corniches : 200 unités. Cadence de préfabrication des corniches : 4 u/j. 

Cadence de pose des corniches : trois cas à étudier : 2 u/j ; 4 u/j et 5 u/j. Délais de durcissement avant le stockage : 1 j. Délais de stockage avant pose : 7 j. Début de la pose J + 91 le matin et la fin de pose J + 140 le soir (J représente le début de chantier). 

Pour calculer les dates et tracer le planning, on applique la convention suivante : 

Les dates de début de tâche sont calculées au matin et les dates de fin de tâche sont données au soir. 

Si le début de préfabrication est calculé à partir de la date de fin, on ajoute 1 jour et inversement. Les éléments fabriqués, stockés et posés sont comptabilisés le soir. 

**Courbe de pose** 

Détermination de la cadence de pose :

On ajoute (+ 1 j) pour tenir compte du décalage du soir et du matin : 

→ Date de début de pose = J+91 

→ Date de fin de pose = J+140 

**Courbe de fabrication** 

La durée de fabrication est déterminée par la formule suivante : 

Durée de fabrication=Quantité à fabriquéCadence de fabrication 

|Cadence<br>de|fabrication|(**2 unités/jour) :**|
|---|---|---|
|Durée=2002=100 jours|||
|Cadence<br>de|fabrication|(**4 unités/jour) :**|
|Durée=2004=50 jours|||
|Cadence<br>de|fabrication|(**5 unités/jour) :**|

- Durée=2005=40 jours 

- Les dates de fabrication sont calculées en tenant compte de la durée de séchage du béton, qui est égale à 7 jours dans cet exemple. Deux cas se présentent :

- 1[er] cas : la cadence de fabrication est inférieure à la cadence de pose. La cadence de fabrication est de **2 unités/jour** et la cadence de pose est de **4 unités/jour.** 

   - Fin de fabrication = fin de pose – durée de pose (1 j) – durée de séchage 

→ J + (140 – 1 – 7) = J + 132 

Début de fabrication = fin de fabrication + 1 – durée de fabrication 

- → J + (132 + 1 – 100) = J + 33 

- 2[e] cas : la cadence de fabrication est supérieure ou égale à la cadence de pose. La cadence de fabrication est de **5 unités/ jour** et la cadence de pose est **4 unités/jour.** 

- Début de fabrication = début de pose – délai de séchage – durée de pose 

→ J + (91 – 7 – 1) = J + 83 

Fin de fabrication = début de fabrication – 1 + durée fabrication

→ J + (83 – 1 + 40) = J + 122 jusqu’au commencement de la pose. Cette courbe se décompose en trois parties :

- Stock S1 : 

**Courbe de stocks** 

Les éléments préfabriqués sont stockés le lendemain de fabrication. Le nombre maximal des éléments à stocker est calculé par le produit entre la cadence de fabrication et la durée de démoulage, plus la durée de séchage. La courbe de stocks est parallèle à la courbe de fabrication avec un décalage d’un jour (+ 1 du début de fabrication) jusqu’au commencement de la pose. 

Cette courbe se décompose en trois parties : 

S1 = (début de pose – début de stock) × cadence de fabrication 

→ [J + (91 – 34)] * 2 = 114 u (cadence de fabrication 2 u/j) 

- → [J + (91 – 84)] * 4 = 28 u (cadence de fabrication 4 u/j) → [J + (91 – 84)] * 5 = 35 u (cadence de fabrication 5 u/j) 

Le début de stock est égal au début de fabrication plus 1 jour.

- Stock S2 : 

S2 = S1 – (fin de fabrication + 1 – début de pose) × (cadence pose – cadence fabrication) 

→ 114 – [J + (132 + 1 – 91) * (4 – 2)] = 30 u (cadence de fabrication 2 u/j) 

→ 28 – [J + (132 + 1 – 91) * (4 – 4)] = 28 u (cadence de fabrication 4 u/j) 

→ 35 – [J + (124 + 1 – 91) * (4 – 5)] = 69 u (cadence de fabrication 5 u/j)

- Stock S3 : 

S3 = S2 + (cadence de fabrication – cadence de pose) 

→ 30 + (2 – 4) = 28 u (cadence de fabrication 2 u/j) 

→ 28 + (4 – 4) = 28 u (cadence de fabrication 4 u/j) 

→ 69 + (5 – 4) = 70 u (cadence de fabrication 5 u/j) 

Tous les calculs sont récapitulés dans le **tableau 4.23** .

|**Courbe de**<br>**production**||**Dates et cadences**||
|---|---|---|---|
|_Courbe de pose_<br>_Date de début de pose_<br>_(au matin)_<br>_Date de fn de pose (au_<br>_soir)_<br>_Nombre de regards (u)_<br>_Cadence de pose par_<br>_jour (u/j)_||_J + 91_<br>_J + 140_<br>_200_<br>_4_||
|_Courbe de fabrication_<br>_Délai de durcissement_<br>_avant la pose (j)_<br>_Cadence de fabrication_<br>_(u/j)_<br>_Durée de fabrication (j)_<br>_Date de fn de_<br>_fabrication (soir)_<br>_Date de début de_<br>_fabrication (matin)_|_7_<br>_2_<br>_100_<br>_J + 132_<br>_J + 33_|_7_<br>_4_<br>_50_<br>_J + 132_<br>_J + 83_|_7_<br>_5_<br>_40_<br>_J + 122_<br>_J + 83_|
|_Courbe de stocks_<br>_Délai de durcissement_<br>_(j)_<br>_Date de début de stock_<br>_Nombre d’éléments en_<br>_stock en début de pose_<br>_S1 (u)_<br>_Nombre d’éléments en_<br>_stock en début de pose_<br>_S2 (u)_<br>_Nombre d’éléments en_<br>_stock en début de pose_<br>_S3 (u)_|_1_<br>_J + 34_<br>_114_<br>_30_<br>_28_|_1_<br>_J + 84_<br>_28_<br>_28_<br>_28_|_1_<br>_J + 84_<br>_35_<br>_69_<br>_70_|

Les **fgures 4.59** , **4.60** et **4.61** présentent les courbes des trois cas étudiés.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0186-00.png]]

_**Figure 4.59 Courbe de production : cas d’une cadence de fabrication supérieure à la cadence de pose**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0187-00.png]]

_**Figure 4.60 Courbe de production : cas d’une cadence de fabrication égale à la cadence de pose**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0188-00.png]]

_**Figure 4.61 Courbe de production : cas d’une cadence de fabrication inférieure à la cadence de pose**_
