---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.1"
ordre_document: 26
titre: "Technique de potentiel-étape : méthode PERT"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 26 Technique de potentiel-étape : méthode PERT
resume_section: |-
  ### 4.1 Technique de potentiel-étape : méthode PERT
  
  La méthode PERT repose sur un réseau de flèches représentant les tâches et leurs interdépendances. Elle permet de visualiser les contraintes, les délais et le chemin critique d’un projet.
  
  #### Terminologie clé :
  - **Graphe** : Schéma composé de nœuds (étapes) et flèches (tâches).
  - **Étape** : Point de début ou fin d’une ou plusieurs tâches, sans durée ni consommation de ressources.
  - **Tâche réelle** : Activité consommant temps et ressources.
  - **Tâche fictive** : Lien symbolique pour représenter des contraintes d’enchaînement, sans durée.
  - **Chemin critique** : Plus long chemin du réseau, définissant la durée totale du projet. Toute tâche critique a une marge nulle.
  
  #### Calculs principaux :
  1. **Dates au plus tôt (TE)** : Calculées en suivant le sens des flèches.
  2. **Dates au plus tard (TL)** : Calculées en sens inverse.
  3. **Marges** :
     - **Totale (MT)** : Retard maximal sans affecter la durée du projet.
     - **Libre (ML)** : Retard sans impacter les tâches suivantes.
     - **Indépendante (MI)** : Retard absorbable sans modifier les dates des tâches précédentes ou suivantes.
     - **Conditionnelle (MC)** : Retard possible si les tâches suivantes commencent au plus tard.
  
  #### Exemple 1 :
  - Durée totale : 42 jours.
  - Chemin critique : A, E, G, H, I.
  - Tâches non critiques (B, C, D, F) ont des marges permettant une flexibilité.
  
  #### Exemple 2 :
  - Modification des prédécesseurs de la tâche E.
  - Nouvelle durée : 37 jours.
  - Chemin critique : E, G, H, I.
  - Réduction des marges pour certaines tâches (ex. B : MT = 3 jours, ML = 0 jour).
  
  Les marges et le chemin critique sont essentiels pour optimiser la gestion des délais et des ressources.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[25-techniques-de-planification|Techniques de planification]]"
section_suivante: "[[27-application-4-1|Application 4-1]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["26_4.1_technique_de_potentiel-étape_méthode_pert.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.1 Technique de potentiel-étape : méthode PERT 

**Principe de la méthode** 

Dans la méthode PERT, le déroulement et l’enclenchement des tâches sont visualisés au moyen d’un réseau plus au moins complexe de flèches, d’où son nom de planning flèche. Ce réseau de symbole fait figurer : 

les contraintes particulières de certaines étapes ; la relativité des délais de début et de fin d’exécution des tâches

- par rapport à l’ensemble du projet et des autres tâches, ainsi que le respect du délai accordé pour leur réalisation. 

- **Terminologie** 

- Pour tracer un réseau et calculer les durées par la méthode PERT, il est utile d’en connaître les termes clés :

- Graphe : c’est le schéma du réseau composé d’un ensemble de nœuds, ou sommets, et d’un ensemble de flèches qui relient entre eux tous les nœuds (voir **fg. 4.1** ). Ce graphe se nomme « réseau » dans le système PERT. _**Figure 4.1 Graphe d’un réseau PERT**_ 

- Étape (ou événement) : elle représente l’un des différents 

**Terminologie** 

Pour tracer un réseau et calculer les durées par la méthode PERT, il est utile d’en connaître les termes clés : 

- sommets du graphe, appelée aussi borne ou événement. Elle ne consomme aucun moyen et a une durée nulle. L’étape marque le début d’une ou plusieurs tâches ou la fin d’une ou plusieurs opérations. Elle est caractérisée par la date d’arrivé au plus tôt (TE), la date d’arrivé au plus tard (TL) et le battement. La **fgure [4.2](27_4.2_application_4-1.md)** présente les caractéristiques de l’étape 3 du graphe de la **fgure 4.1** .

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0092-00.png]]

**Figure [4.2](27_4.2_application_4-1.md) Détails représentés dans une étape** 

- Tâche réelle, activité ou intervention : la tâche, ou opération réelle, est symbolisée par un trait continu terminé par une flèche précisant l’ordre de succession des tâches. Une opération réelle consomme du temps et des ressources (voir **fg. [4.3](28_4.3_application_4-2.md)** ). _**Figure 4.3 Représentation d’une opération réelle**_ 

- Tâche fictive : une opération fictive est symbolisée par un trait discontinu orienté, utilisé pour visualiser une contrainte d’enchaînement qui lie deux étapes situées sur des chemins différents. Dans la **fgure [4.4](29_4.4_étude_de_cas_des_liaisons_avec_décalage_du_réseau_des_antécédents.md)** , la tâche J est une tâche fictive qui entraîne une liaison de dépendance entre les tâches F et G avec la tâche B. Il faut signaler qu’une tâche fictive peut modifier la durée du projet et le battement d’une étape, bien

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0093-00.png]]

**----- Start of picture text -----**<br>
qu’elle ait une durée nulle.<br>Figure [4.4](29_4.4_étude_de_cas_des_liaisons_avec_décalage_du_réseau_des_antécédents.md) Représentation du graphe contenant une opération fictive<br>•  Séquence logique (ou chemin) : elle est composée par une<br>**----- End of picture text -----**<br>

- succession d’opérations dont l’ordre d’exécution ne peut être modifié. La **fgure [4.5](30_4.5_technique_gantt.md)** présente une séquence logique de la mise en œuvre de poteaux en béton armé, formée de six étapes et cinq tâches. _**Figure 4.5 Représentation d’une séquence logique**_ 

- Chemin critique : c’est le chemin le plus long qui définit la durée totale d’exécution du projet. Il passe par toutes les étapes qui ont des battements nuls et représente sa colonne vertébrale. Le chemin critique est formé des tâches critiques qui ont des dates au plus tôt égales aux dates au plus tard. Il est représenté par une flèche foncée ou brisée (voir **fg. [4.6](31_4.6_application_4-3.md)** ). Tout retard dans l’exécution d’une tâche critique aura une incidence sur la date de fin des travaux. Dans un réseau, on peut avoir plus d’un chemin critique. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0093-02.png]]

Déterminer les dates d’arrivée au plus tôt et au plus tard de la durée du projet suit plusieurs étapes : 

1. Calcul des dates d’arrivée au plus tôt – TEi – des différentes tâches en suivant le sens des flèches, appelé sens « aller ». 

2. Détermination de la durée du projet. La date d’arrivée au plus tôt de l’étape finale correspond à la date d’arrivée au plus tard du projet et représente la durée du projet. 

3. Détermination des dates d’arrivée au plus tard – TLi – des différentes tâches en suivant un sens contraire des flèches, appelé sens « retour ». 

4. Évaluation des marges de chaque tâche et le battement de chaque étape. 

**5. Établissement du chemin critique.** 

Pour expliquer la méthode de détermination des dates de réalisation et des marges, ainsi que le chemin critique, nous reprenons les données de l’exemple n° 1 du chapitre 3 présentées dans le tableau suivant. 

_**Tableau 4.1 Tableau des tâches de l’exemple n° 1**_ 

|**Activité**|**Prédécesseur**|**Durée (j)**|
|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A_<br>_B_<br>_C ; F_<br>_A_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_5_<br>_3_<br>_15_<br>_6_<br>_4_<br>_18_<br>_14_<br>_14_<br>_5_|

**Calcul des dates au plus tôt** 

Pour déterminer les dates d’arrivée au plus tôt des différentes tâches, on utilise la terminologie présentée dans la **fgure [4.7](32_4.7_application_4-4.md)** .

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0095-00.png]]

_**Figure [4.7](32_4.7_application_4-4.md) Représentation d’une tâche**_ 

À partir de l’étape d’origine, prise pour instant zéro, on progresse de la gauche vers la droite, selon le sens des flèches, en additionnant de proche en proche les durées prévues. Lorsque plusieurs chemins aboutissent à une même étape, c’est le temps du plus long parcours qui est tenu comme date d’arrivée au plus tôt. Pour déterminer les dates d’arrivée au plus tôt – TEj – du réseau, on utilise la formule suivante : 

_Date d’arrivée au plus tôt de la tâche (j) : TEj = TEi + te(i-j)_ 

On peut détailler les calculs des dates d’arrivée au plus tôt des tâches C et E du réseau de l’exemple 1 de la manière suivante (voir **fg. [4.8](33_4.8_application_4-5.md)** ) : 

_TE4 = TE2 + te(E) = 5 + 4 = 9 jours,_ 

_TE5 = max {TE3 + te(C) et TE4 + te(F)} = max {8 + 15 et 9 + 18} = 27 jours_ 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0095-07.png]]

_**Figure [4.8](33_4.8_application_4-5.md) Calcul des dates d’arrivée au plus tôt**_ 

**Détermination de la durée du projet**

indique la fin du projet dont la date d’arrivée au plus tôt est égale à la date d’arrivée au plus tard : TE8 = TL8 = 42 jours. Cela donne une durée de projet de 42 jours. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0096-01.png]]

_**Figure [4.9](34_4.9_planning_chemin_de_fer_génie_civil.md) Calcul de la durée de projet**_ 

**Calcul des dates au plus tard** 

Pour déterminer la date au plus tard (TL), il faut parcourir le graphe en sens contraire des flèches. En partant de l’étape finale jusqu’à l’étape d’origine, on retranche successivement les durées des tâches parcourues. Si plusieurs chemins conduisent à une même étape, c’est le résultat le plus faible qui sera retenu comme date d’arrivée au plus tard de l’étape concernée. On utilise la formule suivante pour déterminer les dates d’arrivée au plus tard TLi. 

_Date d’arrivée au plus tard de la tâche (i) : TLi = TLj – te(i-j)_ 

On peut détailler le calcul des dates d’arrivée au plus tôt des tâches D et G de la manière suivante (voir **fg. [4.10](35_4.10_application_4-6.md)** ). 

_TL5 = TL7 – te(D) = 37 – 6 = 31 jours_ 

_TL4 = min {TL5 – te(F) et TL6 – te(G)} = min {31 – 18 et 23 – 14} = 9 jours,_ 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0096-09.png]]

_**Figure [4.10](35_4.10_application_4-6.md) Calcul des dates d’arrivée au plus tard**_

Il faut noter qu’on doit avoir au minimum une tâche initiale qui a une date d’arrivée au plus tard nulle. 

**Calcul des marges** 

**Calcul des marges** 

Les marges représentent une durée disponible permettant de décaler l’exécution de certaines tâches en cas de retard ou d’indisponibilité des ressources. Les marges permettent de gérer l’exécution en phase de travaux. On distingue les marges totales, les marges libres, les marges conditionnelles et les marges indépendantes. 

**Marge totale d’une opération** 

C’est le retard maximal possible dans l’exécution d’une tâche, sans allonger le délai du projet, mais en autorisant de décaler la réalisation des autres tâches. La marge totale d’une tâche MT(i-j) se calcule avec l’opération suivante : 

_MT(i-j)  = TLj – (TEi + te(i-j))_ 

On peut détailler le calcul des marges totales des tâches B et F ainsi (voir **fg. [4.11](36_4.11_application_4-7.md)** ) : 

_MT(B)  = TL3 – (TE2 + teB) = 16 – (5 + 3) = 8 jours, MT(F)  = TL5 – (TE4 + teF) = 31 – (9 + 18) = 4 jours_ 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0097-09.png]]

**Marge libre d’une opération** 

C’est le retard maximal possible dans l’exécution d’une tâche, non seulement sans allonger le délai du projet, mais aussi sans décaler la réalisation des autres tâches. La marge libre d’une opération ML(i-j) est calculée par la formule suivante : 

_ML(i-j) = TEj – (TEi + te(i-j))_ 

Les calculs des marges libre des tâches B et F sont les suivants (voir **fg. [4.11](36_4.11_application_4-7.md)** ) : 

_ML(B)  = TE3 – (TE2 + teB) = 8 – (5 + 3) = 0 jour,_ 

_ML(F)  = TE5 – (TE4 + teF) = 27 – (9 + 18) = 0 jour_ 

**Marge indépendante d’une opération** 

La marge indépendante d’une opération, appelée aussi marge certaine, peut être absorbée sans que les autres activités ne soient modifiées. C’est le retard qu’on peut admettre sur une tâche sans modifier les dates de début au plus tôt des tâches postérieures, à condition que les tâches précédentes aient commencé à leur date au plus tard. On la calcule en faisant l’opération suivante : 

_MI(i-j) = max {0 ; TEj – (TLi + te(i-j))}_ 

Le calcul des marges indépendantes des tâches B et F sont les suivants (voir **fg. 4.12** ) : 

_MI(B)  = max {0 ; TE3 – (TL2 + teB)} = max {0 ; 8 – (5 + 3)} = 0 jour,_ 

_MI(C)  = max {0 ; TE5 – (TL3 + teC)_ } _= max {0 ; 27 – (16 + 15)} = max {0 ; – 4} = 0 jour_ 

**Marge conditionnelle d’une opération** 

La marge conditionnelle est possible à condition que toutes les tâches suivantes commencent au plus tard. On la calcule en faisant l’opération suivante : 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0098-15.png]]

Le calcul des marges conditionnelles des tâches B et C est présenté cidessous (voir **fg. 4.12** ) : 

_MC(B)  = max {0 ; TL3 – (TL2 + teB)} = max {0 ; 16 – (5 + 3)} =_

**8 jours,** 

_MC(C)  = max {0 ; TL5 – (TL3 + teC)} = max {0 ; 31 – (16 + 15)} = 0 jour_ 

D’après les calculs précédents des marges conditionnelles et indépendantes, on prend zéro comme marge si les calculs donnent des valeurs négatives. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0099-03.png]]

- _**Figure 4.12 Calcul des marges indépendantes et conditionnelles**_ 

- **Représentation graphique des marges** 

- Pour mieux comprendre les notions des marges, les **fgures 4.13gures 4.13** et donnent une représentation graphique des marges totales et 

- Dans le cas de la **fgure 4.13** , pour avoir une marge totale de 8 jours dans la réalisation de la tâche (C), il faut que l’exécution de la tâche (D) commence au plus tard. On va donc créer un décalage dans l’exécution des successeurs de la tâche (C) pour avoir une marge totale de 8 jours. On aura cette marge en décalant l’exécution de toutes les tâches qui succèdent à la tâche (C). 

- Dans la même figure, est exposée la méthode de détermination de la marge libre de la tâche (C). On a une marge libre de 4 jours, qui est permise quel que soit le début de la tâche (D), au plus tôt ou au plus tard. Pour avoir cette marge de 4 jours, il n’est pas nécessaire que la tâche (D) commence au plus tard comme dans le cas de la marge totale. On aura cette marge 

**Représentation graphique des marges** 

Pour mieux comprendre les notions des marges, les **fgures 4.13gures 4.13** et **4.14** donnent une représentation graphique des marges totales et libres.

- sans modifier le déroulement d’aucune tâche. 

- La tâche (C) a une marge conditionnelle nulle et une marge 

- indépendante négative qui sera prise égale à zéro. 

- Dans la **fgure 4.14** , on remarque que si la tâche (B) se termine au plus tard (le 16[e] jour), alors la tâche (C) ne peut commencer qu’au plus tard le 16[e] jour et se termine le 31[e ] jour. Dans ce cas, la tâche (D) ne peut commencer qu’après la fin de la tâche (C). De ce fait, on a consommé la marge totale de 8 jours et la marge libre de 4 jours. 

La **fgure 4.15** présente le schéma du réseau PERT de l’exemple n° 1 présenté dans le **tableau 4.1** avec les valeurs des battements, des marges totales et des marges libres. 

_Marge totale de la tâche (C) = TLj – (TEi + te) = 31 – (8 + 15) = 8 jours_ 

_Marge libre de la tâche (C) = TEj – (TEi + te) = 27 – (8 + 15) = 4 jours_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0101-00.png]]

_**Figure 4.13 Représentation des marges, cas des tâches précédentes finissant au plus tôt**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0102-00.png]]

_**Figure 4.14 Représentation des marges, cas des tâches précédentes finissant au plus tard**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0103-00.png]]

_**Figure 4.15 Réseau PERT avec calcul des dates et des marges de l’exemple n° 1**_ 

**Tableau de calcul des marges** 

Les calculs des différentes dates et marges peuvent être représentés sous la forme d’un tableau ( **tab. [4.2](27_4.2_application_4-1.md)** ), appelé tableau de calcul des marges. Les formules utilisées sont : 

_Marge totale : MT(i-j)  = TLj – (TEi + te(i-j)) Marge libre : ML(i-j) = TEj – (TEi + te(i-j)) Marge indépendante : MI(i-j) =_ max {0 ; _TEj – (TLi + te(i-j))_ } _, Marge conditionnelle : MC(i-j) =_ max {0 ; _TLj – (TLi + te(i-j))_ } 

_**Tableau [4.2](27_4.2_application_4-1.md) Tableau de calcul des marges de l’exemple n° 1**_ 

|**Tâche**|**Tâche**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**||**Valeur des marges**|**Valeur des marges**|**Valeur des marges**|
|---|---|---|---|---|---|---|---|---|---|
|**_Nom_**|**_Durée_**|**_Étape de début_**<br>**_(i)_**||**_Étape de fn (j)_**||**_MT_**|**_ML_**|**_MI_**|**_MC_**|
|||**_TE_**|**_TL_**|**_TE_**|**_TL_**|||||
||_(1)_|_(2)_|_(3)_|_(4)_|_(5)_|_5 – (2_<br>_+ 1)_|_4 – (2_<br>_+ 1)_|_4 – (3_<br>_+ 1)_|_5 – (3_<br>_+ 1)_|
|_A_|_5_|_0_|_0_|_5_|_5_|_0_|_0_|_0_|_0_|
|_B_|_3_|_5_|_5_|_8_|_16_|_8_|_0_|_0_|_8_|

|_C_|_15_|_8_|_16_|_27_|_31_|_8_|_4_|_0_|_0_|
|---|---|---|---|---|---|---|---|---|---|
|_D_|_6_|_27_|_31_|_37_|_37_|_4_|_4_|_0_|_0_|
|_E_|_4_|_5_|_5_|_9_|_9_|_0_|_0_|_0_|_0_|
|_F_|_18_|_9_|_9_|_27_|_31_|_4_|_0_|_0_|_4_|
|_G_|_14_|_9_|_9_|_23_|_23_|_0_|_0_|_0_|_0_|
|_H_|_14_|_23_|_23_|_37_|_37_|_0_|_0_|_0_|_0_|
|_I_|_5_|_37_|_37_|_42_|_42_|_0_|_0_|_0_|_0_|

**Détermination du chemin critique** 

Le chemin critique est formé des tâches critiques et représente le plus long chemin qui définit la durée du projet. Dans le réseau de l’exemple n° 1 présenté dans la **fgure 4.15** , le chemin critique est formé de cinq tâches critiques : A, E, G, H et I, et donne une durée de projet de 42 jours. Il passe automatiquement par des étapes ayant un battement nul et des tâches ayant des marges nulles. 

À partir de ce réseau PERT, on remarque que : 

- les tâches A, E, G, H et I sont des tâches critiques ayant la date d’arrivée au plus tôt égale à la date d’arrivée au plus tard ; la tâche A est la seule tâche initiale, donc elle doit obligatoirement être critique. De même pour la tâche I, elle est la seule tâche finale, elle est donc critique ; 

- la tâche B n’est pas critique, elle peut commencer au plus tôt le 5[e] jour et se terminer le 8[e] jour. Au plus tard, elle peut se terminer le 16[e] jour, c’est-à-dire qu’elle peut commencer au plus tard le 13[e] jour ; 

- la tâche B a une marge libre nulle et une marge totale de 8 jours. Pour avoir 8 jours de marge de la tâche B, il faut que la tâche C commence au plus tard ; 

- de même, les tâches C, D et F ne sont pas critiques, elles ont des marges non nulles qui permettent une certaine flexibilité dans la gestion pendant la période d’exécution. 

**Étude du réseau PERT de l’exemple n° 2** 

On présente dans la **fgure 4.16** le graphe du réseau PERT et les calculs des dates de l’exemple n° 2 du chapitre 3 dont les données sont présentées dans le **tableau [4.3](28_4.3_application_4-2.md)** . Les calculs des marges libres et

_**Tableau [4.3](28_4.3_application_4-2.md) Tableau des tâches de l’exécution de l’exemple n° 2**_ 

|**Activité**|**Prédécesseur**|**Durée (j)**|
|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A_<br>_B_<br>_C ; F_<br>_Néant_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_5_<br>_3_<br>_15_<br>_6_<br>_4_<br>_18_<br>_14_<br>_14_<br>_5_|

À la suite du changement des prédécesseurs de la tâche E de l’exemple n° 1, on remarque que : 

la durée du projet est passée à 37 jours au lieu de 42 jours. Cette diminution de 5 jours correspond à la durée de la tâche A prédécesseur de la tâche E dans l’exemple n° 1 ; 

les tâches A et E sont des tâches initiales, seule la tâche E est critique ; le chemin critique est formé des tâches E, G, H et I ; des changements ont lieu au niveau des marges des tâches A, B, C, D et F. La tâche B n’a que 3 jours de marge totale dans son exécution, c’est-à-dire qu’il faut que la tâche C commence au plus tard, sinon la marge sera nulle, ce qui correspond à la marge libre de la tâche (B). 

_MT(B)  = TL4 – (TE2 + teB) = 11 – (5 + 3) = 3 jours,_ 

_ML(B)  = TE4 – (TE2 + teB) = 8 – (5 + 3) = 0 jour,_ exemple de la tâche F, 

_MT(F)  = TL5 – (TE3 + teF) = 26 – (4 + 18) = 4 jours, ML(F)  = TE5 – (TE3 + teF) = 23 – (4 + 18) = 1 jour,_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0106-00.png]]

_**Figure 4.16 Réseau PERT avec calcul des dates et des marges de l’exemple n° 2**_ 

_**Tableau [4.4](29_4.4_étude_de_cas_des_liaisons_avec_décalage_du_réseau_des_antécédents.md) Tableau de calcul des marges de l’exemple n° 2**_ 

|**Tâche**|**Tâche**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**|**Dates d’arrivée**|**Valeur des marges**|**Valeur des marges**|
|---|---|---|---|---|---|---|---|
|||**_Étape de début (i)_**||**_Étape de fn (j)_**||||
|**_Nom_**|**_Durée_**|**_TE_**|**_TL_**|**_TE_**|**_TL_**|**_MT_**|**_ML_**|
|_A_|_5_|_0_|_0_|_5_|_8_|_3_|_0_|
|_B_|_3_|_5_|_8_|_8_|_11_|_3_|_0_|
|_C_|_15_|_8_|_11_|_23_|_26_|_3_|_0_|
|_D_|_6_|_23_|_26_|_32_|_32_|_3_|_3_|
|_E_|_4_|_0_|_0_|_4_|_4_|_0_|_0_|
|_F_|_18_|_4_|_4_|_23_|_26_|_4_|_1_|
|_G_|_14_|_4_|_4_|_18_|_18_|_0_|_0_|
|_H_|_14_|_18_|_18_|_32_|_32_|_0_|_0_|
