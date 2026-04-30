---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.3"
ordre_document: 28
titre: "Application 4-2"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 28 Application 4-2
resume_section: |-
  ### Résumé du segment 4.3 Application 4-2
  
  L'application 4-2 consiste à planifier la construction d'un entrepôt en 10 tâches. Les étapes incluent :
  1. **Matrice d’antériorité et rangs des tâches** : Déterminés dans le tableau 4.9 et la figure 4.20.
  2. **Réseau PERT** : Dates, marges et chemin critique calculés (tableau 4.10, figure 4.21). La durée du projet est de 17 jours, avec un chemin critique formé des tâches A, E, H et J.
  
  **Méthode des antécédents (PDM)** :
  - Les tâches sont représentées par des nœuds (pavés) et les dépendances par des arcs.
  - Calculs des dates au plus tôt (DTO, FTO) et au plus tard (DTA, FTA) permettent de déterminer la durée du projet, les marges et le chemin critique.
  - Les marges totales (MT) et libres (ML) sont calculées pour chaque tâche.
  
  **Exemples** :
  - Exemple 1 : Durée de 42 jours, chemin critique : A, E, G, H, I.
  - Exemple 2 : Durée réduite à 37 jours, chemin critique : E, G, H, I.
  
  Les résultats des méthodes PERT et PDM sont cohérents.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[27-application-4-1|Application 4-1]]"
section_suivante: "[[29-etude-de-cas-des-liaisons-avec-decalage-du-reseau-des-antecedents|Étude de cas des liaisons avec décalage du réseau des antécédents]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["28_4.3_application_4-2.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.3 Application 4-2 

**Énoncé de l’application 4-2** 

Votre entreprise est chargée de planifier les travaux d’exécution d’un entrepôt, découpés en dix tâches dont les caractéristiques sont données dans le **tableau [4.8](33_4.8_application_4-5.md)** . 

On demande de : 

1. Établir la matrice d’antériorité et déterminer les rangs des tâches. 

2. Tracer les graphes PERT, calculer les dates de réalisation des tâches, les marges et déterminer le chemin critique. 

_**Tableau [4.8](33_4.8_application_4-5.md) Données des tâches de l’application 4-2**_ 

**Tâche Désignation Tâche antérieure Durée (jours)**

|_A_<br>|_Acceptation des plans_<br>_ar le roriétaire_|_Néant_<br>|_4_<br>|
|---|---|---|---|
|_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_<br>_J_|_p  pp_<br>_Préparation du terrain_<br>_Commande des_<br>_matériaux_<br>_Excavation des fouilles_<br>_Commande des portes_<br>_et fenêtres_<br>_Livraison des matériaux_<br>_Bétonnage des_<br>_fondations_<br>_Livraison des portes et_<br>_fenêtres_<br>_Pose des murs, de la_<br>_charpente et de la_<br>_toiture_<br>_Mise en place des portes_<br>_et fenêtres_|_Néant_<br>_A_<br>_A, B_<br>_A_<br>_C_<br>_D, F_<br>_E_<br>_G_<br>_H, I_|_2_<br>_1_<br>_1_<br>_2_<br>_2_<br>_2_<br>_10_<br>_4_<br>_1_|
|||||

**Corrigé de l’application 4-2** 

On présente dans le **tableau [4.9](34_4.9_planning_chemin_de_fer_génie_civil.md)** et la **fgure 4.20** les résultats de détermination des rangs des tâches et la matrice d’antériorité. 

Les résultats de calcul des dates, de la durée d’exécution et des marges des différentes tâches sont présentés dans le **tableau [4.10](35_4.10_application_4-6.md)** et la **fgure 4.21** . 

_**Tableau [4.9](34_4.9_planning_chemin_de_fer_génie_civil.md) Tableau des rangs de l’application 4-2**_ 

**Tâche Désignation Tâche antérieure Rang**

||_A_|||_Acceptation des plans_||_Néant_|||_1_||
|---|---|---|---|---|---|---|---|---|---|---|
||_B_|||_par le propriétaire_||_Néant_|||_1_||
||_C_|||_Préparation du terrain_||_A_|||_2_||
||_D_|||_Commande des_||_A, B_|||_2_||
||_E_|||_matériaux_||_A_|||_2_||
||_F_|||_Excavation des fouilles_||_C_|||_3_||
||_G_<br>_H_|||_Commande des portes_<br>_et fenêtres_<br>_Livraison des matériaux_||_D, F_<br>_E_|||_4_<br>_3_||
||_I_<br>_J_|||_Bétonnage des_<br>_fondations_||_G_<br>_H, I_|||_5_<br>_6_||
|||||_Livraison des portes et_|||||||
|||||_fenêtres_|||||||
|||||_Pose des murs, de la_|||||||
|||||_charpente et de la_|||||||
|||||_toiture_|||||||
|||||_Mise en place des portes_|||||||
|||||_et fenêtres_|||||||
||||||||||||
|**Rang**||_1_||_2_<br>_3_||_4_||_5_||_6_|
|**Tâche**||_A et B_||_C, D et E_<br>_F et_|_H_|_G_||_I_||_J_|

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0114-00.png]]

_**Figure 4.20 Matrice d’antériorité de l’application 4-2**_ 

_**Tableau [4.10](35_4.10_application_4-6.md) Tableau de calcul des marges de l’application 4-2**_ 

|**Tâche**|**Tâche**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**|**Valeur des marges**|**Valeur des marges**|
|---|---|---|---|---|---|---|---|
|**_Nom_**|**_Durée_**|**_Étape de début (i)_**||**_Étape de fn (j)_**||**_MT_**|**_ML_**|
|||**_TE_**|**_TL_**|**_TE_**|**_TL_**|||
|_A_|_4_|_0_|_0_|_4_|_4_|_0_|_0_|
|_B_|_2_|_0_|_0_|_4_|_9_|_7_|_2_|
|_C_|_1_|_4_|_4_|_5_|_8_|_3_|_0_|
|_D_|_1_|_4_|_9_|_7_|_10_|_5_|_2_|
|_E_|_2_|_4_|_4_|_6_|_6_|_0_|_0_|
|_F_|_2_|_5_|_8_|_7_|_10_|_3_|_0_|
|_G_|_2_|_7_|_10_|_9_|_12_|_3_|_0_|
|_H_|_10_|_6_|_6_|_16_|_16_|_0_|_0_|
|_I_|_4_|_9_|_12_|_16_|_16_|_3_|_3_|

À partir du réseau PERT et du tableau de calcul des marges, on en déduit : 

La durée de projet est de 17 jours. Le chemin critique est formé des tâches A, E, H et J. On remarque aussi que toutes les marges libres sont toujours inférieures ou égales aux marges totales. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0115-03.png]]

_**Figure 4.21 Réseau PERT avec calcul des dates de l’application 4-2**_ 

**Technique de potentiel-tâche : méthode des antécédents « PDM »**

Le principe de la méthode repose toujours sur un modèle mathématique, c’est-à-dire un réseau composé de sommets et de flèches : 

les sommets, ou nœuds, représentent les tâches et non plus des étapes comme dans la méthode PERT. On les appelle généralement pavés ou boîtes ; les arcs, ou vecteurs, représentent les contraintes de liaison ou la dépendance entre les tâches, et non plus les tâches ellesmêmes comme dans la méthode PERT. 

La tâche, sous la forme d’un pavé (voir **fg. 4.22** ), peut être représentée d’une manière plus ou moins détaillée : soit en indiquant seulement les dates et la durée, soit de manière plus complète, en indiquant tous les renseignements telles que les dates de début ou de fin au plus tôt et au plus tard, les durées et les marges. La tâche est repérée par son nom complet ou abrégé, par une lettre ou le plus souvent par la lettre « T » suivie d’un numéro. Quatre dates calculées : DTO, FTO, DTA et FTA sont associées à chaque tâche. 

DTO : date de Début de tâche au plus tôt FTO : date de Fin de tâche au plus tôt DTA : date de Début de tâche au plus tard FTA : date de Fin de tâche au plus tard

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0117-00.png]]

_**Figure 4.22 Représentation des tâches selon la méthode de potentiel-tâche**_ 

Pour tracer un réseau des antécédents, on procède de la manière suivante : 

1. On détermine les rangs des tâches, la matrice d’antériorité et on trace le graphe. 

2. On calcule les dates de début et de fin au plus tôt (DTO et FTO) 

« sens aller ». 

3. On détermine la durée du projet. 

4. On calcule les dates de début et de fin au plus tard (DTA et FTA) 

« sens retour ». 

5. On calcule les différentes marges. 

6. On détermine le chemin critique. 

Si la durée de projet ne convient pas à celle prévue par le maître d’ouvrage, on peut soit réduire la durée d’exécution des tâches en

multipliant les ressources, soit créer des chevauchements entre les tâches, en utilisant des liens avec décalage. 

**Contraintes entre les tâches** 

Les tâches sont dépendantes les unes des autres et leurs liaisons sont définies par des contraintes d’enclenchement. Le **tableau [4.11](36_4.11_application_4-7.md)** présente les quatre types de liens possibles entre les différentes tâches d’un projet. Le lien courant, ou par défaut, est du type FinDébut (FD), c’est-à-dire que lorsque la tâche (i) se termine, la tâche (j) commence. Dans ce type de lien, on ne note rien sur la flèche de liaison. Si le lien est avec décalage, on note sur la flèche FD±d. 

_**Tableau [4.11](36_4.11_application_4-7.md) Les contraintes entre les tâches**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0119-00.png]]

Le décalage « d » entre les tâches peut être positif, négatif ou nul. La **fgure 4.23** présente les quatre types de lien avec décalage entre une tâche Ti de durée (7 jours) et une tâche T(i + 1) de durée

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0122-01.png]]

**Calcul des dates au plus tôt et au plus tard** 

Pour calculer les différentes dates des tâches du réseau des antécédents, on applique la même méthodologie que dans la méthode PERT. La **fgure 4.24** représente le réseau des antécédents de l’exemple n° 1 du **tableau [4.1](26_4.1_technique_de_potentiel-étape_méthode_pert.md)** avec les calculs des dates et des durées. Les liens entre les tâches sont tous du type Fin-Début sans décalage (on ne note rien sur la flèche). 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0122-04.png]]

_**Figure 4.24 Réseau des antécédents de l’exemple n° 1 avec calcul des durées**_ 

**Date au plus tôt** 

On commence par la tâche initiale ayant comme début zéro, en calculant de la gauche vers la droite, dans le « sens aller », les dates

au plus tôt de début et de fin de chaque tâche. La tâche finale, qui a la plus longue date de fin au plus tôt, nous fournit la durée d’exécution du projet. La tâche finale a les mêmes dates de début et de fin au plus tôt et au plus tard. La terminologie utilisée dans les calculs est présentée dans la **fgure 4.25** . 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0123-01.png]]

_**Figure 4.25 Schématisation des dates au plus tôt**_ 

La méthode de calcul des dates de début et de fin au plus tôt est la suivante : 

- **DTOj :** elle est calculée à partir de l’origine du projet vers la fin, en suivant les liens, et en prenant la plus grande valeur 

- quand plusieurs sont obtenues. 

- **FTOi :** on ajoute à chaque date au plus tôt DTOi la durée de la tâche (i). 

**DTOj = DTOi + Durée (i)** 

**FTOi = DTOi + Durée (i)**_ **→** _**DTOj = FTOi** 

La **fgure 4.26** présente les détails de calcul des dates au plus tôt de la tâche D du réseau des antécédents de l’exemple N° 1. 

_DTOD = max {DTOC + Durée(C), DTOF + Durée(F)} = max {8 + 15, 9 + 18} = 27 jours_ 

_Autrement dit : DTOD = max {FTOC, FTOF} = max {23, 27} = 27 jours_ 

_FTOD = DTOD + Durée(D) = 27 + 6 = 33 jours_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0124-00.png]]

_**Figure 4.26 Calcul des dates au plus tôt de l’exemple n° 1 par la méthode des antécédents**_ 

**Durée de projet** 

La tâche « I » est une tâche finale, elle définit la durée du projet de 42 jours (voir **fg. 4.27** ). 

_DTOI = max {DTOD + Durée(D), DTOH + Durée(H)}_ 

→ _DTOI = max {27 + 6, 23 + 14} = 37 jours FTOI = DTOI + Durée(I) = 37 + 5 = 42 jours FTOI = FTAI = 42 jours = Durée du projet_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0125-00.png]]

_**Figure 4.27 Calcul de la durée de projet de l’exemple n° 1 par la méthode des antécédents**_ 

**Date au plus tard** 

On commence les calculs par la tâche finale ayant comme date au plus tard la durée d’exécution du projet, obtenue par le calcul suivant le sens aller. On détermine alors à quelles dates de début au plus tard doivent être exécutées les tâches sans remettre en cause cette date de fin du projet. Ce calcul se fait de la droite vers la gauche, appelé sens retour. Puis on calcule la date de fin au plus tard de chaque tâche (voir **fg. 4.28** ). 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0125-04.png]]

- **DTAi :** elle est calculée à partir de la fin du projet vers l’origine en suivant les liens, en prenant la plus petite valeur quand plusieurs sont obtenues. 

- **FTAi :** on ajoute à chaque date DTA **i** la durée de la tâche (i) 

**DTAi = DTAj – durée (i)** 

**FTAi = DTAi + Durée (i)**_ **→** _**FTAi = DTAj** 

La **fgure 4.29** présente les détails de calcul des dates au plus tard de la tâche E. 

_DTAE = min {DTAF – Durée(E), DTAG – Durée(E)} = min {13 – 4, 9 – 4} = 5 jours, FTAE = DTAE + Durée(E) = 5 + 4 = 9 jours_ 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0126-05.png]]

_**Figure 4.29 Calcul des dates au plus tard de l’exemple n° 1 par la méthode des antécédents**_ 

**Calcul des marges et détermination du chemin critique** 

Chaque tâche a donc une durée maximale disponible pour son exécution égale à FTO moins DTO. Chaque tâche est caractérisée par la marge totale et la marge libre qu’elle a sur les chemins qu’elle compose. 

**Marge totale MT** 

Elle est égale à la différence entre FTAi et FTOi ou entre DTAi et DTOi d’une même tâche (i). C’est la plage de temps maximum au cours de laquelle une tâche peut se déplacer sans modifier la date de terminaison du projet, mais en acceptant de décaler le commencement des autres tâches. Les tâches critiques ont par conséquent une marge totale égale à zéro :

**MTi = DTAi – DTOi = FTAi – FTOi** 

Le calcul des marges totales des tâches C et E est comme suit (voir **fg. 4.30** ) : 

_MTC = DTAC – DTOC = FTAC – FTOC = 16 – 8 = 31 – 23 = 8 jours, MTE = DTAE – DTOE = FTAE – FTOE = 5 – 5 = 9 – 9 = 0 jour_ 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0127-03.png]]

_**Figure 4.30 Calcul des marges de l’exemple n° 1 par la méthode des antécédents**_ 

**Marge libre ML** 

Elle est égale à la différence entre la plus petite des DTOj des tâches immédiatement suivantes et la FTOi de la tâche considérée. La marge libre correspond à la plage de temps au cours de laquelle la tâche peut se déplacer librement **sans modifier** aucune des dates de début au plus tôt des tâches immédiatement postérieures. 

**MLi = min {DTOj – FTOi}** 

Le calcul des marges libres des tâches C et E est le suivant (voir **fg. 4.30** ) : 

_MLC = DTOD – FTOC = 27 – 23 = 8 jours, MLE = min {DTOF – FTOE et DTOG – FTOE} = min {9 – 9 et 9 – 9} =_

La marge libre d’une activité est toujours inférieure, tout au plus égale, à la marge totale. 

**MLTâche ≤ MTTâche** 

**Chemin critique** 

Comme pour la méthode PERT, le chemin critique est composé des tâches critiques ayant des marges nulles définissant la durée d’exécution du projet. On peut avoir plus d’un chemin critique dans un même projet. 

Dans le réseau des antécédents de la **fgure 4.31** , on a fait les calculs des marges totales et libres de chaque tâche du même exemple n° 1 du **tableau [4.1](26_4.1_technique_de_potentiel-étape_méthode_pert.md)** , étudié avec la méthode PERT. On trouve les mêmes résultats que ceux déterminés par la méthode PERT présentés dans la **fgure 4.15** : 

le chemin critique est formé de cinq tâches : A, E, G, H, et I ; la durée du projet est de 42 jours ; les mêmes valeurs des marges trouvées précédemment indiquées dans le **tableau [4.2](27_4.2_application_4-1.md)** .

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0129-00.png]]

_**Figure 4.31 Réseau des antécédents avec calcul des dates et des marges de l’exemple n° 1**_ 

**Étude du réseau des antécédents de l’exemple n° 2** 

On présente dans la **fgure 4.32** le réseau des antécédents de l’exemple n° 2. 

Les principaux changements par rapport au réseau de l’exemple n° 1 sont : 

on a deux tâches initiales A et E ; la durée de projet est passée à 37 jours au lieu de 42 jours ; le chemin critique est formé des tâches E, G, H, I ; la tâche A, bien qu’elle soit initiale, n’est pas critique. 

Par comparaison au réseau PERT de l’exemple n° 2 étudié auparavant, on trouve les mêmes résultats. La durée du projet est de

37 jours et les valeurs des marges des différentes tâches et le chemin critique sont les mêmes (voir **fg. 4.32** ). 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0130-01.png]]

_**Figure 4.32 Réseau des antécédents de l’exemple n° 2 avec le calcul des dates et des marges**_
