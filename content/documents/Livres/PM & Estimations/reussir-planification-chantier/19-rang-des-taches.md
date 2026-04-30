---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:3.7"
ordre_document: 19
titre: "Rang des tâches"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 19 Rang des tâches
resume_section: |-
  ### 3.7 Rang des tâches
  
  Le rang des tâches, essentiel pour le traçage d’un planning par méthode des réseaux, est déterminé selon l’ordre logique des activités. Les tâches sans prédécesseur sont au rang 1, celles dépendant du rang précédent au rang suivant, et ainsi de suite. Si une tâche a plusieurs prédécesseurs de rangs différents, on prend le rang maximal + 1.
  
  **Exemple 1 :**
  Un projet de 9 tâches (A à I) est analysé. Les rangs sont attribués en fonction des prédécesseurs. Résultat : 5 rangs, avec un tableau récapitulatif des tâches par rang.
  
  **Exemple 2 :**
  En modifiant les prédécesseurs de la tâche E (sans prédécesseur), les rangs sont recalculés. Résultat : toujours 5 rangs, mais des ajustements dans la répartition des tâches (ex. F et G passent au rang 2). Un tableau actualisé illustre ces changements.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[18-application-3-1|Application 3-1]]"
section_suivante: "[[20-representation-matricielle|Représentation matricielle]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["19_3.7_rang_des_tâches.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 3.7 Rang des tâches 

**Principes** 

Pour faciliter le traçage d’un planning par la méthode des réseaux (potentiel-étape et potentiel-tâche), il est nécessaire de déterminer les rangs d’enclenchement des différentes tâches. En suivant une séquence logique des activités, le numéro de rang indique l’ordre de réalisation de la tâche. Pour classer les rangs, on affecte les numéros des rangs de chaque tâche de la manière suivante : 

**Rang n° 1 :** tâches n’ayant pas de tâches antérieures. **Rang n° 2 :** tâches ayant des tâches antérieures du rang (1). **Rang n° n :** tâches ayant des tâches antérieures du rang (n-1) au moins. 

**Détermination des rangs des tâches : exemple n° 1** 

Le **tableau [3.8](20_3.8_représentation_matricielle.md)** présente un premier exemple d’un projet formé de neuf tâches (A, B, …I). Chaque tâche est caractérisée soit par ses successeurs soit par ses prédécesseurs. 

_**Tableau [3.8](20_3.8_représentation_matricielle.md) Méthode de détermination des rangs, exemple n° 1**_ 

**Activité Prédécesseur Successeur**

|_A_<br>_B_|_Néant_<br>_A_|_B ; E_<br>_C_|
|---|---|---|
|_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_B_<br>_C ; F_<br>_A_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_D_<br>_I_<br>_F ; G_<br>_D_<br>_H_<br>_I_<br>_Néant_|

- Pour déterminer, les rangs on procède de la manière suivante : La tâche A n’a pas d’antécédent (prédécesseur), elle est alors une tâche initiale et prend le 1[er] rang. Pour faciliter la détermination des rangs, on insère un indice « 1 » en dessous de la tâche A de la liste des prédécesseurs (voir **tab. [3.9](21_3.9_liaisons_entre_les_tâches.md)** ). Les tâches B et E ont comme prédécesseur la tâche A, elles prennent le rang numéro 2. De même, on insère un indice 2 sur les prédécesseurs B et E. La tâche C commence après la fin de la tâche B du 2[e] rang, elle sera placée dans le 3[e] rang. De la même manière, on détermine les rangs de toutes les tâches. Au total, on a cinq rangs. Si une tâche a deux prédécesseurs de rangs différents, on prend le rang maximal et on ajoute 1. 

Pour faciliter le traçage du graphe correspondant, on dresse un tableau récapitulatif des rangs formé de deux lignes indiquant les numéros des rangs et les tâches correspondantes. 

_**Tableau [3.9](21_3.9_liaisons_entre_les_tâches.md) Méthode de détermination des rangs, corrigé de l’exemple n° 1**_ 

|**Activité**|**Activité**|**Prédécesseur**|**Prédécesseur**|**Rang**|**Rang**|
|---|---|---|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_||_Néant_<br>_A1_<br>_B2_<br>_C3 ; F3_<br>_A1_<br>_E2_<br>_E2_<br>_G3_<br>_D4 ; H4_|||_1_<br>_2_<br>_3_<br>_4_<br>_2_<br>_3_<br>_3_<br>_4_<br>_5_|
|||||||
|**Rang**|_1_|_2_|_3_|_4_|_5_|
|**Tâche**|_A_|_B et E_|_C, F et G_|_D et H_|_I_|

On reprend les mêmes tâches de l’exemple n° 1, en opérant un changement dans la liste des prédécesseurs de la tâche « E ». Cette tâche n’a plus de prédécesseur. Il s’agit alors de déterminer les nouveaux rangs des tâches (voir **tab. [3.10](22_3.10_construction_des_graphes.md)** ). 

_**Tableau [3.10](22_3.10_construction_des_graphes.md) Méthode de détermination des rangs, exemple n° 2**_ 

|**Activité**|**Prédécesseur**|**Successeur**|
|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A_<br>_B_<br>_C ; F_<br>_Néant_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_B_<br>_C_<br>_D_<br>_I_<br>_F ; G_<br>_D_<br>_H_<br>_I_<br>_Néant_|

En comparant avec le tableau des rangs de l’exemple n° 1 ( **tab. [3.9](21_3.9_liaisons_entre_les_tâches.md)** ), on remarque que : 

Il n’y a pas de changement dans le nombre total des rangs, il y en a toujours 5. 

Il y a deux tâches initiales dans le 1[er] rang, A et E, car elles n’ont pas de prédécesseurs. 

Les tâches F et G ont pris le 2[e] rang au lieu du 3[e] , puisqu’elles sont précédées de la tâche initiale E qui a changé de prédécesseur et de rang. 

La tâche D a pris le 4[e] rang, qui est le maximum des rangs des tâches C (rang 3) et F (rang 2) plus un. 

_**Tableau 3.11 Méthode de détermination des rangs, exemple n° 2**_ 

**Activité Prédécesseur Rang**

||_A_|_A_|||_Néant_|_Néant_|||_1_|_1_||
|---|---|---|---|---|---|---|---|---|---|---|---|
||_B_||||_A1_||||_2_|||
||_C_||||_B2_||||_3_|||
||_D_||||_C3 ; F2_||||_4_|||
||_E_||||_Néant_||||_1_|||
||_F_||||_E1_||||_2_|||
||_G_||||_E1_||||_2_|||
||_H_||||_G2_||||_3_|||
||_I_||||_D4 ; H3_||||_5_|||
|||||||||||||
|**Rang**|||_1_|_2_|||_3_|_4_|||_5_|
|**Tâche**|||_A et E_|_B, F et G_|||_C et H_|_D_|||_I_|
