---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.8"
ordre_document: 33
titre: "Application 4-5"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 33 Application 4-5
resume_section: |-
  L'application 4-5 concerne la planification de la construction de deux bâtiments industriels, impliquant préfabrication et pose d'éléments. Les tâches sont détaillées dans le tableau 4.19. Les objectifs sont :
  
  1. Déterminer le rang des tâches (résultats dans le tableau 4.20, 9 rangs identifiés).
  2. Tracer le réseau des antécédents, calculer les dates de début/fin au plus tôt et au plus tard, les marges, et identifier le chemin critique (tâches H, I, G, K, O, V, W). La durée totale du projet est de 53 jours (résultats dans la figure 4.50 et tableau 4.21).
  3. Construire un diagramme de GANTT, incluant le chemin critique (figures 4.51 et 4.52).
  
  Les marges totales et libres pour chaque tâche sont également fournies.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[32-application-4-4|Application 4-4]]"
section_suivante: "[[34-planning-chemin-de-fer-genie-civil|Planning chemin de fer (génie civil)]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["33_4.8_application_4-5.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.8 Application 4-5

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0160-00.png)

_**Figure 4.49 Diagramme GANTT de l’application 4-4**_

La construction de deux bâtiments industriels nécessite la préfabrication et la pose de nombreux éléments. Les informations sur les différentes tâches constitutives du projet sont présentées dans le **tableau 4.19** . 

**On demande de :** 

**1. Déterminer le rang de chaque tâche.** 

2. Tracer le réseau des antécédents et déterminer la date de commencement au plus tôt, au plus tard et les marges de chaque tâche et en déduire le chemin critique. 

3. Construire le planning GANTT en faisant apparaître le chemin critique. 

_**Tableau 4.19 Données des tâches de l’application 4-5**_ 

|**N°**|**Désignation des**<br>**tâches**|**Durée**|**Tâche antérieure**|
|---|---|---|---|
|**_A_**|_Implantation générale_|_2_|_/_|
|**_B_**|_Terrassement bât A_|_3_|_A_|
|**_C_**|_Terrassement bât B_|_3_|_B_|
|**_D_**|_Fondation bât A_|_5_|_B(DD + 1)_|
|**_E_**|_Fondation bât B_|_5_|_D, C(DD + 1)_|
|**_F_**|_Pose poteaux_<br>_préfabriqués bât A_|_8_|_D(DD + 2), H (FF_<br>_+ 5)_|
|**_G_**|_Pose poteaux_<br>_préfabriqués bât B_|_8_|_E (DD + 2), I(FF_<br>_+ 5), F_|
|**_H_**|_Préfabrication des_<br>_poteaux bât A_|_12_|_/_|
|**_I_**|_Préfabrication des_<br>_poteaux bât B_|_12_|_H_|
|**_J_**|_Pose des poutres_<br>_préfabriquées bât A_|_4_|_F, L(FF + 4)_|
|**_K_**|_Pose des poutres_<br>_préfabriquées bât B_|_4_|_G, M(FF + 4), J_|
|**_L_**|_Préfabrication des_<br>_poutres bât A_|_8_|_/_|
|**_M_**|_Préfabrication des_<br>_poutres bât B_|_8_|_L_|

|**_N_**|_Pose des pannes_<br>_préfabriquées du bât A_|_7_|_J, P(FF + 5)_|
|---|---|---|---|
|**_O_**||_7_|_K, Q(FF + 5), N_|
||_Pose des pannes_<br>_préfabriquées du bât B_|||
|**_P_**|_Préfabrication des_<br>_pannes bât A_|_7_|_M_|
|**_Q_**|_Préfabrication des_<br>_pannes bât B_|_7_|_P_|
|**_R_**|_Pose des lisses_<br>_préfabriqués bâts A_|_6_|_J, T(DD + 4)_|
|**_S_**|_Pose des lisses_<br>_préfabriqués bât B_|_6_|_K, U(DD + 4), R_|
|**_T_**|_Préfabrication des lisses_<br>_bâts A_|_6_|_I_|
|**_U_**|_Préfabrication des lisses_<br>_bâts B_|_6_|_T_|
|**_V_**|_Mise en place bacs des_<br>_aciers pour les_<br>_bâtiments A et B_|_8_|_O_|
|**_W_**|_Mise en place des_<br>_bardages pour les_<br>_bâtiments A et B_|_10_|_V(DD + 3), S_|

**Corrigé de l’application 4-5** 

1. On présente dans le **tableau 4.20** les rangs des tâches. Au total, il y a 9 rangs. 

2. La **fgure 4.50** présente le réseau des antécédents dans lequel sont présentées les dates de début et de fin au plus tôt et au plus tard. La durée de projet obtenue est de 53 jours, les marges totales et libres sont présentées dans le **tableau 4.21** . Le chemin critique est formé des tâches : H, I, G, K, O, V et W. 

3. Les **fgures 4.51** et **4.52** présentent le diagramme de GANTT et le diagramme de GANTT élaboré par MS Project. 

_**Tableau 4.20 Tableau des rangs de l’application 4-5**_ 

|**Rang 1**|**Rang 2**|**Rang 3**|**Rang 4**|**Rang 5**|**Rang 6**|**Rang 7**|**Rang 8**|**Rang 9**|
|---|---|---|---|---|---|---|---|---|
|_A_<br>_H_<br>_L_|**_B_**<br>**_I_**<br>**_M_**|_C_<br>_D_<br>_T_<br>_P_|_E_<br>_F_<br>_U_<br>_Q_|_G_<br>_J_|_K_<br>_N_<br>_R_|_O_<br>_S_|_V_|_W_|

|**N°**|**Désignation des**<br>**tâches**|**Durée (jours)**|**Marge totale**<br>**(jours)**|**Marge libre**<br>**(jours)**|
|---|---|---|---|---|
|**_A_**|_Implantation_<br>_générale_|_2_|_8_|_0_|
|**_B_**|_Terrassement bât_<br>_A_|_3_|_8_|_0_|
|**_C_**|_Terrassement bât_<br>_B_|_3_|_13_|_2_|
|**_D_**|_Fondation bât A_|_5_|_8_|_0_|
|**_E_**|_Fondation bât B_|_5_|_11_|_11_|
|**_F_**|_Pose poteaux_<br>_préfabriqués bât A_|_8_|_4_|_0_|
|**_G_**|_Pose poteaux_<br>_préfabriqués bât B_|_8_|_0_|_0_|
|**_H_**|_Préfabrication des_<br>_poteaux bât A_|_12_|_0_|_0_|
|**_I_**|_Préfabrication des_<br>_poteaux bât B_|_12_|_0_|_0_|
|**_J_**|_Pose des poutres_<br>_préfabriquées bât_<br>_A_|_4_|_5_|_0_|
|**_K_**|_Pose des poutres_<br>_préfabriquées bât_<br>_B_|_4_|_0_|_0_|
|**_L_**|_Préfabrication des_<br>_poutres bât A_|_8_|_5_|_0_|
|**_M_**|_Préfabrication des_<br>_poutres bât B_|_8_|_5_|_0_|
|**_N_**|_Pose des pannes_<br>_préfabriquées du_<br>_bât A_|_7_|_5_|_5_|
|**_O_**|_Pose des pannes_<br>_préfabriquées du_<br>_bât B_|_7_|_0_|_0_|
|**_P_**|_Préfabrication des_<br>_pannes bât A_|_7_|_5_|_0_|
|**_Q_**|_Préfabrication des_<br>_pannes bât B_|_7_|_5_|_5_|
|**_R_**|_Pose des lisses_<br>_préfabriqués bâts_<br>_A_|_6_|_3_|_0_|
|**_S_**|_Pose des lisses_<br>_préfabriqués bât B_|_6_|_3_|_3_|
|**_T_**|_Préfabrication des_<br>_lisses bâts A_|_6_|_3_|_0_|

|**_U_**|_Préfabrication des_<br>_lisses bâts B_|_6_|_3_|_0_|
|---|---|---|---|---|
|**_V_**||_8_|_0_|_0_|
||_Mise en place bacs_<br>_des aciers pour les_<br>_bâtiments A et B_||||
|**_W_**|_Mise en place des_<br>_bardages pour les_<br>_bâtiments A et B_|_10_|_0_|_0_|

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0166-00.png)

_**Figure 4.50 Réseau des antécédents de l’application 4-5**_

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0168-00.png)
