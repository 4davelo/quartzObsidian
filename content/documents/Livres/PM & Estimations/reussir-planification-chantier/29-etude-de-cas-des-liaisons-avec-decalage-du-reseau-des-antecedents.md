---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.4"
ordre_document: 29
titre: "Étude de cas des liaisons avec décalage du réseau des antécédents"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 29 Étude de cas des liaisons avec décalage du réseau des antécédents
resume_section: |-
  ### 4.4 Étude de cas des liaisons avec décalage du réseau des antécédents
  
  L'ajout de liaisons avec décalage (DD, DF, FD, FF) modifie les marges et la durée du projet, portée à 40 jours. Les décalages sont intégrés dans le réseau des antécédents, avec calculs détaillés des dates (DTO, DTA, FTO, FTA) et des marges (MT, ML). Les formules spécifiques à chaque type de lien sont présentées, accompagnées d'exemples concrets pour les tâches A, B, E, F, G et H. Les figures illustrent les calculs pour chaque type de liaison.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[28-application-4-2|Application 4-2]]"
section_suivante: "[[30-technique-gantt|Technique GANTT]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["29_4.4_étude_de_cas_des_liaisons_avec_décalage_du_réseau_des_antécédents.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.4 Étude de cas des liaisons avec décalage du réseau des antécédents 

Des contraintes entre les tâches, autres que les liens courants du type

Fin-Début, ont une incidence sur les marges et la durée du projet. Le **tableau 4.12** introduit des nouveaux liens avec décalage entre les tâches du **tableau [4.1](26_4.1_technique_de_potentiel-étape_méthode_pert.md)** de l’exemple n° 1. Les liens sont du type : Début-Début (DD), Début-Fin (DF), Fin-Début (FD) et Fin-Fin (FF). Les liens avec le décalage sont notés sur la flèche correspondante dans le réseau des antécédents. Dans la **fgure 4.33** , on présente le réseau des antécédents avec tous les calculs des dates, de durée, des marges et le chemin critique relatifs à cet exemple. 

_**Tableau 4.12 Tableau des tâches de l’exemple n° 3, liens avec des décalages**_ 

|**Activité**|**Prédécesseur**|**Durée (j)**|
|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A (DD + 3j)_<br>_B_<br>_C ; F (FD – 3j)_<br>_A (FD + 4j)_<br>_E (DF + 20j)_<br>_E_<br>_G (FF + 8j)_<br>_D ; H_|_5_<br>_3_<br>_15_<br>_6_<br>_4_<br>_18_<br>_14_<br>_14_<br>_5_|

À la suite de ce changement au niveau des contraintes entre les liens des tâches, on trouve que la durée du projet est portée à 40 jours.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0132-00.png]]

_**Figure 4.33 Réseau des antécédents de l’exemple n° 3 avec le calcul des dates et des marges**_ 

Les formules utilisées pour déterminer les dates, les durées et les marges pour les quatre types de lien avec décalage sont présentées dans le **tableau 4.13** . La méthodologie et les détails de l’application des formules de calcul des durées et des marges pour chaque type de lien sont détaillés ci-après. 

_**Tableau 4.13 Formules de calcul des dates et des marges**_ 

|**Type de lien**|**_DTO, FTO, DTA, FTA, MT et ML_**|**_DTO, FTO, DTA, FTA, MT et ML_**|
|---|---|---|
|**_Début-Début_**|**_Au plus tôt (j)_**|_DTOj = DTOi + décalage_|
|**_DD_**||_FTOj = DTOj + durée (j)_|
||**_Au plus tard (i)_**|_DTAi = DTAj – décalage_|
|||_FTAi = DTAi + durée (i)_|
||||

|**_Début-Fin_**<br>**_DF_**|**_Marges (i)_**|_MTi = DTAi – DTOi_ _= FTAi –_<br>_FTOi_<br>_ML(i) = DTOj – (DTOi_<br>_+ décalage)_|
|---|---|---|
||**_Au plus tôt (j)_**||
|||_FTOj = DTOi + décalage_<br>_DTOj = FTOj – durée (j)_|
||**_Au plus tard (i)_**|_DTAi = FTAj – décalage_<br>_FTAi = DTAi + durée (i)_|
||**_Marges (i)_**|_MTi = DTAi – DTOi_ _= FTAi –_<br>_FTOi_<br>_ML(i) = FTOj – (DTOi_<br>_+ décalage)_|
|**_Fin-Début_**<br>**_FD_**|**_Au plus tôt (j)_**|_DTOj = FTOi_ _+ décalage_<br>_FTOj_ _= DTOj+ durée (j)_|
||**_Au plus tard (i)_**|_DTAi = DTAj – (Durée (i)_<br>_+ décalage)_<br>_FTAi = DTAi + durée (i)_|
||**_Marges (i)_**|_MTi = DTAi_ _– DTOi_ _= FTAi –_<br>_FTOi_<br>_ML(i) = DTOj – (FTOi_<br>_+ décalage)_|
|**_Fin-Fin_**<br>**_FF_**|**_Au plus tôt (j)_**|_FTOj = FTOi_ _+ décalage_<br>_DTOj = FTOj – durée (j)_|
||**_Au plus tard (i)_**|_FTAi = FTAj_ _– décalage_<br>_DTAi = FTAi – durée (i)_|
||**_Marges (i)_**|_MTi = DTAi – DTOi_ _= FTAi –_<br>_FTOi_<br>_ML(i) = FTOj – (FTOi_<br>_+ décalage)_|

**Lien Début-Début, DD + décalage** 

Les détails de calcul des dates DTO, DTA, FTO et FTA et de la marge libre sont présentés dans les formules suivantes et les **fgures 4.34** et **4.35** . La méthode de calcul de la marge totale ne change pas, quel que soit le type de lien. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0133-03.png]]

**Date au plus tôt : cas de la tâche B** 

_DTOj = DTOi + décalage_ → _DTOB = DTOA + décalage = 0 + 3 = 3 jours_ 

_FTOi = DTOi + Durée (i)_ → _FTOB = DTOB + durée (B) = 3 + 3 = 6 jours_ 

**Date au plus tard : cas de la tâche A** 

_DTAi = DTAj – décalage_ → _DTAA = min {DTAB – décalage et DTAE – (durée (A) + décalage} = DTAA = min {13 – 3 et 9 – (5 + 4)} = 0 FTAi = DTAi + Durée (i)_ → _FTAA = DTAA + durée (A) = 0 + 5 = 5 jours_ 

**Marge libre : cas de la tâche A** 

_ML(i) = DTOj – (DTOi + décalage)_ → _ML(A) = min {DTOB – (DTOA + d) et DTOE – (FTOA + décalage)}_ → _ML(A) = min {3 – (0 + 3) et 9 – (5 + 4)} = 0_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0135-00.png]]

_**Figure 4.35 Calcul des dates et des marges dans le cas d’un lien Début-Début avec décalage**_ 

**Lien Début-Fin, DF + décalage** 

La méthode et les détails de calcul des dates DTO, DTA, FTO et FTA et de la marge libre sont présentés dans les formules suivantes et les **fgures 4.36** et **4.37** . 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0135-04.png]]

_**Figure 4.36 Liaison Début-Fin avec décalage**_

_FTOj = DTOi + décalage_ → _FTOF = DTOE + décalage = 9 + 20 = 29 jours_ 

_FTOi = DTOi + Durée (i)_ → _DTOi = FTOi – Durée (i)_ 

_DTOF = FTOF – durée (F) = 29 – 18 = 11 jours_ 

**Date au plus tard : cas de la tâche E** 

_DTAi = FTAj – décalage_ → _DTAE = min {FTAF – décalage et DTAG – durée (E)}_ 

_DTAE = min {32 – 20 et 13 – 4} = 9 jours_ 

_FTAi = DTAi + Durée (i)_ → _FTAE = DTAE + durée (E) = 9 + 4 = 13 jours_ 

**Marge libre : cas de la tâche E** 

_ML(i) = FTOj – (DTOi + d)_ → _ML(E) = min {FTOF – (DTOE + d) et DTOG – FTOE}_ 

_ML(E)_ _**=** min {29 – (9 + 20) et 13 – 13} = 0_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0137-00.png]]

_**Figure 4.37 Calcul des dates et des marges, cas de lien Début-Fin avec décalage**_ 

**Lien Fin-Début, FD + décalage** 

Les détails de calcul des dates DTO, DTA, FTO et FTA et de la marge libre sont présentés dans les formules suivantes et les **fgures 4.38** et **4.39** . 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0137-04.png]]

_**Figure 4.38 Liaison Fin-Début avec décalage**_

_DTOj = FTOi + d_ → _DTOE = FTOA + d = 5 + 4 = 9 jours FTOj = DTOj + Durée (j)_ → _FTOE = DTOE + Durée (E) = 9 + 4 = 13 jours_ 

**Date au plus tard : cas de la tâche F** 

_DTAi = DTAj – (Durée (i) + d) et FTAi = DTAi + Durée (i) DTAF = DTAD – (Durée (F) + d)_ → _FTAF = DTAF + Durée (F)_ → _DTAF = 29 – (18 – 3) = 14 jours et FTAF = 14 + 18 = 32 jours ou bien FTAF = DTAD – d = 29 – (–3) = 32 jours_ 

**Marge libre : cas de la tâche F** 

_ML(i) = DTOj – (FTOi + d) ML(F) = DTOD – (FTOF + d) = 26 – (29 – 3) = 0 jour_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0139-00.png]]

_**Figure 4.39 Calcul des dates et des marges cas de lien Fin-Début avec décalage**_ 

**Lien Fin-Fin, FF + décalage** 

Les détails de calcul des dates DTO, DTA, FTO et FTA et de la marge libre sont présentés dans les formules suivantes et les **fgures 4.40** et **4.41** .

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0140-00.png]]

_**Figure 4.40 Liaison Fin-Fin avec décalage**_ 

**Date au plus tôt : cas de la tâche H** 

_FTOj = FTOi + d_ → _FTOH = FTOG + d = 27 + 8 = 35 jours_ 

_DTOj = FTOj – Durée (j)_ → _DTOH = FTOH – Durée (H) = 35 – 14 = 21 jours_ 

**Date au plus tard : cas de la tâche G** 

_FTAi = FTAj – d_ → _FTAG = FTAH – d = 35 – 8 = 27 jours_ 

_DTAi = FTAi – Durée (i)_ → _DTAG = FTAG – Durée (G) = 27 – 14 = 13 jours_ 

**Marge libre : cas de la tâche G** 

_ML(i) = FTOj – (FTOi + d)_ → _ML(G) = FTOH – (FTOG + d) = 35 – (27 + 8) = 0 jour_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0141-00.png]]

_**Figure 4.41 Calcul des dates et des marges, cas de lien Fin-Fin avec décalage**_
