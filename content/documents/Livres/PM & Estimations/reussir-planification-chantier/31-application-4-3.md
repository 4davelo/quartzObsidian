---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.6"
ordre_document: 31
titre: "Application 4-3"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 31 Application 4-3
resume_section: |-
  **Résumé :**
  
  L'application 4-3 analyse le planning d'un chantier à partir des données du tableau 4.14. Les étapes incluent :
  1. Tracer le réseau des antécédents, calculer les dates (DTO, FTO, DTA, FTA), les marges totales (MT), libres (ML) et la durée du projet (53 jours), puis identifier le chemin critique.
  2. Réaliser le diagramme GANTT.
  3. Comparer les résultats des deux méthodes, qui s'avèrent identiques.
  
  Les calculs détaillés des dates et marges montrent que toutes les tâches, sauf H, ont des marges nulles, confirmant leur appartenance au chemin critique. Les résultats sont synthétisés dans les tableaux 4.14 et 4.15, et illustrés par les figures 4.45 (réseau des antécédents) et 4.46 (diagramme GANTT).
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[30-technique-gantt|Technique GANTT]]"
section_suivante: "[[32-application-4-4|Application 4-4]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["31_4.6_application_4-3.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.6 Application 4-3

On veut étudier le planning d’un chantier avec les informations présentées dans le **tableau 4.14** . On demande de : 

1. Tracer le réseau des antécédents et calculer les dates, les marges totales, les marges libres et la durée du projet puis en déduire le chemin critique. 

2. Tracer le diagramme GANTT. 

3. Comparer les résultats des deux méthodes. 

_**Tableau 4.14 Données des tâches de l’application 4-3**_ 

|**Tâche**|**Durée en jours**|**Tâche antérieure**|**Rang**|
|---|---|---|---|
|_A_|_5_|_/_|_1_|
|_B_|_7_|_A (DD + 3)_|_2_|
|_C_|_10_|_B (DD + 10j)_|_3_|
|_D_|_15_|_B (DD + 5j)_|_3_|
|_E_|_15_|_C (FF + 10j) ; D (FF_<br>_+ 10j)_|_4_|
|_F_|_10_|_E_|_5_|
|_G_|_4_|_D ; F (DF + 10j)_|_6_|
|_H_|_5_|_C (FD + 5j)_|_4_|
|_I_|_5_|_F ; G (FF + 10j) ; H_<br>_(FF + 10j)_|_7_|

**Corrigé de l’application 4-3** 

1. Le réseau des antécédents et les valeurs des marges sont présentés dans la **fgure 4.45** et le **tableau 4.15** . Les détails de calcul des dates et des durées sont les suivants : 

**Calcul des durées sens aller, DTO et FTO :** 

- Tâche A : 

_La tâche A est initiale_ → _DTOA = 0_ 

_FTOA = DTOA + Durée (A)_ → _FTOA = 0 + 5 = 5 jours_

- Tâche B : 

   - _DTOB = DTOA + décalage_ → _DTOB = 0 + 3 = 3 jours_ 

   - _FTOB = DTOB + Durée (B)_ → _FTOB = 3 + 7 = 10 jours_ 

- Tâche C : 

   - _DTOC = DTOB + décalage_ → _DTOC = 3 + 10 = 13 jours_ 

   - _FTOC = DTOC + Durée (C)_ → _FTOC = 13 + 10 = 23 jours_ 

- Tâche D : 

   - _DTOD = DTOB + décalage_ → _DTOD = 3 + 5 = 8 jours_ 

   - _FTOD = DTOD + Durée (D)_ → _FTOD = 8 + 15 = 23 jours_ 

- Tâche E : 

   - _FTOE = max {FTOD + décalage et FTOC + décalage}_ 

   - → _FTOE = max { 23 + 10 et 23 + 10} = 33 jours_ 

   - _DTOE = FTOE – Durée (E)_ → _DTOE = 33 – 15 = 18 jours_ 

- Tâche F : 

   - _DTOF = DTOE + durée (E) = FTOE_ → _DTOF = 18 + 15 = 33 jours_ 

   - _FTOF = DTOF + Durée (F)_ → _FTOF = 33 + 10 = 43 jours_ 

- Tâche G : 

   - _DTOG = max {FTOD et DTOF + décalage – durée (G)}_ → _DTOG = max {23 et 33 + 10 – 4} = 39 jours_ 

   - _FTOG = DTOG + Durée (G)_ → _DTOG = 39 + 4 = 43 jours_ 

- Tâche H : 

   - _DTOH = FTOC + décalage_ → _DTOH = 23 + 5 = 28 jours_ 

   - _FTOH = DTOH + Durée (H)_ → _FTOH = 28 + 5 = 33 jours_ 

- Tâche I : 

   - _DTOI = max {FTOF, FTOG + décalage – durée (I) et FTOH + décalage – durée (I)}_ 

   - → _DTOE = max { 43, 43 + 10 – 5 et 33 + 10 – 5} = 48 jours_ 

   - _FTOI = DTOI + Durée (I)_ → _DTOI = 48 + 5 = 53 jours_ 

- **La durée du projet :** la durée d’exécution du projet est de 53 jours.

**Calcul des durées sens retour DTA, FTA et des marges MT et ML** 

On commence de la tâche finale et on progresse dans le sens contraire des flèches. 

- Tâche I : 

- _La tâche I est finale_ → _DTAI = DTOI, et FTAI = FTOI_ → _ML = MT = 0_ 

- Tâche H : 

- _FTAH = FTAI – décalage_ → _FTAH = 53 – 10 = 43 jours DTAH = FTAH – Durée (H)_ → _DTAH = 43 – 5 = 38 jours_ 

- _MTH = DTAH – DTOH ou FTAH – FTOH = 38 – 28 = 10 jours_ 

- _MLH = FTOI – (FTOH + décalage) = 53 – (33 + 10) = 10 jours_ 

- Tâche G : 

- _FTAG = FTAI – décalage_ → _FTAG = 53 – 10 = 43 jours DTAG = FTAG – Durée (G)_ → _FTAG = 43 – 4 = 39 jours_ 

- _MTG = DTAG – DTOG ou FTAG – FTOG = 39 – 39 = 0 jour_ 

- _MLG = FTOI – (FTOH + décalage) = 53 – (43 + 10) = 0 jour_ 

- Tâche F : 

- _DTAF = min {DTAI – durée (F) et FTAG – décalage}_ 

- → _DTAF = min {48 – 10 et 43 – 10} = 33 jours_ 

- _FTAF = DTAF + Durée (F)_ → _FTAF = 33 + 10 = 43 jours MTF = DTAF – DTOF ou FTAF – FTOF = 33 – 33 = 0 jour_ 

- _MLF = min {DTOI – FTOF ; FTOG – (DTOF + décalage)}_ 

- → _MLF = min {48 – 43 ; 43 – (33 + 10)} = 0 jour_ 

- Tâche E : 

- _DTAE = DTAF – durée (E)_ → _DTAE = 33 – 15 = 18 jours FTAE = DTAE + Durée (E)_ → _FTAE = 18 + 15 = 33 jours MTE = DTAE – DTOE ou FTAE – FTOE = 33 – 33 = 0 jour_ 

- _MLE = DTOF – FTOE_ → _MLE = 33 – 33 = 0 jour_ 

- Tâche D :

- _DTAD = min {FTAE- décalage – durée (D) et DTAG – durée (D)}_ → _DTAD = min {33 – 10 – 15 et 39 – 15} = 8 jours FTAD = DTAD + Durée (D)_ → _FTAD = 8 + 15 = 23 jours MTD = DTAD – DTOD ou FTAD – FTODD = 23 – 23 = 0 jour MLD = min {DTOG – FTOD et FTOE – (FTOD + décalage)}_ 

- → _MLD = min {39 – 23 et 33 – (23 + 10)} = 0 jour_ 

- Tâche C : 

- _DTAC = min {FTAE – décalage – durée (C) et DTAH – durée (C) – décalage}_ 

- _DTAC = min {33 – 23 – 10 et 38 – 10 – 5}_ → _DTAC = 13 jours FTAC = DTAC + Durée (C)_ → _FTAC = 13 + 10 = 23 jours MTC = DTAC – DTOC ou FTAC – FTOC = 13 – 13 = 0 jour_ 

- _MLC = = min {FTOE – (FTOC + décalage) et DTOH – (FTOC + décalage)}_ 

- → _MLC = min {33 – (23 + 10) et 28 – (23 + 5)} = 0 jour_ 

- Tâche B : 

- _DTAB = min {DTAC – décalage et DTAD – décalage}_ 

- → _DTAB = min {13 – 10 et 8 – 5} = 3 jours_ 

_FTAB = DTAB + Durée (B)_ → _FTAB = 3 + 7 = 10 jours_ 

- _MTB = DTAB – DTOB ou FTAB – FTOB = 3 – 3 = 0 jour_ 

- _MLB = min {DTOC – (DTOB + décalage) et DTOD – (DTOB + décalage)}_ 

- → _MLB = min {13 – (3 + 10) et 8 – (3 + 5)} = 0 jour_ 

- Tâche A : 

- _DTAA = DTAB– décalage_ → _DTAA = 3 – 3 = 0 jour_ 

- _FTAA = DTAA + Durée (A)_ → _FTAA = 0 + 5 = 5 jours_ 

- _MTA = DTAA– DTOA ou FTAA – FTOA = 0 jour_ 

- _MLA = DTOB – (DTOA + décalage)_ → _MLA = 3 – (0 + 3) = 0 jour_

**Tableau des marges** 

_**Tableau 4.15 Tableau récapitulatif des marges de l’application 4-3**_ 

|**Tâche**|**Durée (jours)**|**Tâche**<br>**antérieure**|**MT**<br>**(jours)**|**ML**<br>**(jours)**|
|---|---|---|---|---|
|_A_|_5_|_/_|_0_|_0_|
|_B_|_7_|_A (DD + 3)_|_0_|_0_|
|_C_|_10_|_B (DD + 10j)_|_0_|_0_|
|_D_|_15_|_B (DD + 5j)_|_0_|_0_|
|_E_|_15_|_C (FF + 10j) ; D_<br>_(FF + 10j)_|_0_|_0_|
|_F_|_10_|_E_|_0_|_0_|
|_G_|_4_|_D ; F (DF + 10j)_|_0_|_0_|
|_H_|_5_|_C (FD + 5j)_|_10_|_10_|
|_I_|_5_|_F ; G (FF + 10j) ;_<br>_H (FF + 10j)_|_0_|_0_|

**Diagramme GANTT et réseaux des antécédents** 

Le diagramme GANNT est présenté dans la **fgure 4.46** . On trouve les mêmes résultats par les deux méthodes.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0151-00.png]]

_**Figure 4.45 Réseau des antécédents de l’application 4-3**_

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0152-00.png]]

_**Figure 4.46 Diagramme GANTT de l’application 4-3**_
