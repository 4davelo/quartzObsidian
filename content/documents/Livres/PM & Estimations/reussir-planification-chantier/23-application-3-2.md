---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:3.11"
ordre_document: 23
titre: "Application 3-2"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 23 Application 3-2
resume_section: |-
  **Résumé du segment 3.11 Application 3-2 :**
  
  L'application 3-2 illustre la planification de travaux de terrassement via les méthodes PERT et PDM. Un projet de 12 tâches est analysé, avec leurs prédécesseurs et rangs déterminés. Les réseaux PERT et des antécédents montrent les relations entre tâches. Points clés : une tâche initiale (A), une tâche finale (L), et des tâches avec plusieurs prédécesseurs (K, L) ou successeurs (B, H). Les figures et tableaux détaillent les cycles, plannings et matrices d'antériorité.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[22-construction-des-graphes|Construction des graphes]]"
section_suivante: "[[24-application-3-3|Application 3-3]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["23_3.11_application_3-2.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 3.11 Application 3-2

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0081-00.png)

_**Figure 3.14 Composantes d’un cycle de travaux de terrassement en déblai**_ 

Dans un système d’axes formé de la distance à parcourir entre le chantier et la décharge en ordonnées, et du temps en abscisses, on trace les cycles des camions de terrassement en faisant apparaître la notion de temps et d’espace. Dans la **fgure 3.15** , on présente le cycle de rotation de quatre camions de transport de déblai. 

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0081-03.png)

_**Figure 3.15 Présentation du planning chemin de fer des travaux de terrassement**_

**Énoncé de l’application 3-2** 

On présente, dans le **tableau 3.13** , un exemple de projet formé de douze tâches. On demande de déterminer les rangs des tâches, d’élaborer la matrice et de tracer les réseaux de la méthode PERT et de la méthode des antécédents PDM. 

_**Tableau 3.13 Données des tâches de l’application 3-2**_ 

|**N°**|**Tâche**|**Prédécesseur**|
|---|---|---|
|_1_|_A_|_Néant_|
|_2_|_B_|_A_|
|_3_|_C_|_B_|
|_4_|_D_|_C_|
|_5_|_E_|_D_|
|_6_|_F_|_B_|
|_7_|_G_|_A_|
|_8_|_H_|_G_|
|_9_|_I_|_H_|
|_10_|_J_|_H_|
|_11_|_K_|_E ; F_|
|_12_|_L_|_I ; J ; K_|

**Corrigé de l’application 3-2** 

On présente les rangs des différentes tâches dans le **tableau 3.14** et la matrice d’antériorité dans la **fgure 3.16** . 

_**Tableau 3.14 Détermination des rangs des tâches de l’application 3-2**_ 

|**N°**|**Tâche**|**Prédécesseur**|**Rang**|
|---|---|---|---|
|_1_|_A_|_Néant_|_1_|
|_2_|_B_|_A_|_2_|
|_3_|_C_|_B_|_3_|
|_4_|_D_|_C_|_4_|

||_5_|_5_|||_E_|_E_||_D_|_D_|||_5_|_5_||
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
||_6_||||_F_|||_B_||||_3_|||
||_7_||||_G_|||_A_||||_2_|||
||_8_||||_H_|||_G_||||_3_|||
||_9_||||_I_|||_H_||||_4_|||
||_10_||||_J_|||_H_||||_4_|||
||_11_||||_K_|||_E ; F_||||_6_|||
||_12_||||_L_|||_I ; J_|_; K_|||_7_|||
||||||||||||||||
|**Rang**|||_1_|_2_|||_3_|_4_||_5_|_6_|||_7_|
|**Tâche**|||_A_|_B et E_|||_C, F et M_|_D, I et J_||_E_|_K_|||_L_|

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0083-01.png)

À partir des tableaux des tâches et de la matrice d’antériorité on remarque que : 

- on a sept rangs ;

- on a une seule tâche initiale, la tâche A, qui n’a pas de 

- prédécesseur ; 

- on a une seule tâche finale, la tâche L, qui n’a pas de 

- successeur ; 

- les tâches L et K sont précédées de plusieurs tâches : 

   - la tâche K a deux flèches d’entrée dans le graphe provenant des tâches E et F, 

la tâche L a trois flèches d’entrée dans le graphe provenant des tâches I, J et K ; 

- les tâches B et H sont des prédécesseurs de plus qu’une tâche : la tâche B a deux flèches de sortie dans le graphe allant vers les tâches C et F, 

la tâche H a deux flèches de sortie dans le graphe allant vers les tâches I et J. 

Les réseaux de la méthode PERT et des antécédents sont présentés respectivement dans les **fgures 3.17** et **3.18** .

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0085-00.png)

_**Figure 3.17 Réseau PERT de l’application 3-2**_

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0086-00.png)

_**Figure 3.18 Réseau des antécédents de l’application 3-2**_
