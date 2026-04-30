---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:3.10"
ordre_document: 22
titre: "Construction des graphes"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 22 Construction des graphes
resume_section: |-
  ## 3.10 Construction des graphes
  
  ### Principes
  Un graphe représente schématiquement les activités d’un projet et leurs dépendances. Il est construit à partir de la décomposition des tâches et de la matrice d’antériorité. Le sens du temps va de l’origine à la fin. Deux méthodes principales existent :
  - **Potentiel-tâche** : tâches en boîtes reliées par des flèches.
  - **Potentiel-étape (PERT)** : tâches en flèches entre étapes.
  
  ### Méthode potentiel-tâche (PDM)
  1. Lister les rangs horizontalement.
  2. Placer les tâches dans les colonnes correspondantes.
  3. Relier les tâches selon la matrice d’antériorité.
  Exemple : Tâche A mène à B et E ; B mène à C, etc. Les tâches I et D ont deux entrées, A et E deux sorties.
  Les modifications dans un autre exemple (ex. 2) montrent des changements de prédécesseurs et de rangs.
  
  ### Méthode PERT
  Les tâches sont représentées par des flèches entre étapes.
  1. Lister les rangs.
  2. Relier les tâches en respectant les étapes initiales et finales.
  Exemple : A (étapes 1-2) mène à B et E (étapes 3-4). Les changements dans un autre exemple (ex. 2) affectent les prédécesseurs et rangs.
  
  ### Diagramme GANTT
  Représentation linéaire basée sur les durées et liaisons des tâches.
  1. Créer un tableau avec tâches et jours.
  2. Tracer des barres proportionnelles aux durées.
  Exemple : A (5 jours), suivi de B (3 jours) et E (4 jours). Les prédécesseurs multiples déterminent le début des tâches.
  Les modifications dans un autre exemple (ex. 2) affectent les tâches initiales et la durée totale.
  
  ### Planning chemin de fer
  Représentation linéaire pour activités répétitives.
  - **Gestion de production** : Courbes de pose, fabrication et stocks.
  - **Rotation des camions** : Cycle en 4 étapes (chargement, transport, déchargement, retour).
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[21-liaisons-entre-les-taches|Liaisons entre les tâches]]"
section_suivante: "[[23-application-3-2|Application 3-2]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["22_3.10_construction_des_graphes.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 3.10 Construction des graphes 

**Principes** 

Le réseau, ou graphe, est une représentation schématique des différentes activités d’un projet, qui permet de visualiser les liaisons entre elles. La construction du graphe s’appuie sur la décomposition hiérarchique du projet en tâches élémentaires ainsi que leurs relations de dépendance. Cette construction est facilitée par la détermination des rangs et l’élaboration de la matrice d’antériorité. 

Le graphe a toujours une ou plusieurs origine(s) et une ou plusieurs fin(s) et le sens d’écoulement du temps part de l’origine vers la fin. La construction du graphe diffère selon la méthode de représentation du réseau. Dans les méthodes de potentiel-tâche, les tâches sont représentées par des boîtes reliées par des flèches définissants les contraintes de liaison. Dans la méthode potentiel-étape, les liaisons sont représentées par des flèches bornées par des étapes.

**Traçage du réseau potentiel-tâche, méthode des antécédents** 

La méthode des antécédents PDM ( _Precedence Diagram Method_ ) est la plus utilisée, car elle tient compte des diverses liaisons entre les tâches. Les étapes du traçage du graphe de l’exemple n° 1 par la méthode de potentiel-tâche sont (voir **fg. [3.6](18_3.6_application_3-1.md)** ) : 

1. Lister les différents rangs suivant l’axe horizontal. Dans le cas de cet exemple, il y a 5 colonnes ou rangs. 

2. Noter, dans chaque colonne, les différentes tâches selon les rangs déterminés dans le **tableau [3.9](21_3.9_liaisons_entre_les_tâches.md)** . 

3. Schématiser les boîtes représentatives des différentes tâches dans la colonne correspondante de chaque rang. 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0071-05.png]]

_**Figure [3.6](18_3.6_application_3-1.md) Schématisation des tâches selon les rangs de l’exemple n° 1**_ 

4. Relier les tâches par des flèches orientées en suivant la matrice de la **fgure 3.4** , en utilisant les sorties de la tâche (voir **fg. 3.7** ) : de la tâche A on a deux sorties vers les deux tâches B et E ; de la tâche B on a une seule sortie vers la tâche C ; de la tâche C on a une seule sortie vers la tâche D ; de la tâche D on a une seule sortie vers la tâche I ; de la tâche E on a deux sorties vers les deux tâches F et G ; de la tâche F on a une seule sortie vers la tâche D ; de la tâche G on a une seule sortie vers la tâche H ; de la tâche H on a une seule sortie vers la tâche I.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0072-00.png]]

_**Figure 3.7 Traçage du réseau des antécédents de l’exemple n° 1**_ 

Toutes les tâches ont une seule entrée sauf les tâches I et D qui ont deux entrées et toutes les tâches ont une seule sortie à l’exception des tâches A et E qui ont deux sorties. 

On procède de la même manière pour tracer le graphe de potentieltâche de l’exemple n° 2 présenté dans la **fgure [3.8](20_3.8_représentation_matricielle.md)** . En le comparant avec le réseau de l’exemple n° 1, on trouve les différences suivantes : les deux tâches A et E sont initiales puis qu’elles n’ont pas de prédécesseur ; seule la liaison entre E et A a changé, toutes les autres liaisons ont été conservées ; à la suite du changement des prédécesseurs de la tâche E, les tâches F, G et H ont changé de rang.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0073-00.png]]

_**Figure [3.8](20_3.8_représentation_matricielle.md) Traçage du réseau des antécédents de l’exemple n° 2**_ 

**Traçage du réseau potentiel-étape, méthode PERT** 

La méthode de traçage du graphe PERT (voir **fg. [3.9](21_3.9_liaisons_entre_les_tâches.md)** ) diffère de celle du réseau de potentiel-tâche dans la représentation elle-même, puisque les tâches sont représentées par des flèches au lieu de boîtes. Chaque tâche est bornée par une étape initiale et une étape finale. La méthodologie à suivre pour tracer le réseau PERT est la suivante. 

1. Lister les différents rangs suivant un axe horizontal. On affecte les tâches aux rangs correspondants comme pour la méthode de potentiel-tâche. 

2. Le traçage et la liaison entre les tâches se fait comme suit : commencer le graphe par la tâche A, limitée par les étapes 1 et 2, puisqu’elle est la seule dans le 1[er] rang. L’étape 1 indique le début de la tâche A, l’étape 2 sa fin ; de l’étape 2, tracer les deux tâches B et E du 2[e] rang, qui commencent en même temps après la fin de la tâche A. Deux nouvelles étapes 3 et 4 sont créées, marquant respectivement la fin de la tâche B et celle de la tâche E ; suivant le même principe, terminer le traçage de toutes les autres tâches ; la tâche I est une tâche finale limitée par les étapes 7 et 8 : l’étape 8 correspond alors à la fin du projet.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0074-00.png]]

_**Figure [3.9](21_3.9_liaisons_entre_les_tâches.md) Construction du graphe PERT de l’exemple n° 1**_ 

Dans le graphe de l’exemple n° 2 (voir **fg. 3.10** ), la schématisation du réseau PERT change. Pour les liaisons, il y a un seul changement au niveau des tâches A et E, puisque la tâche E est devenue une tâche initiale. Le changement du réseau et le décalage des rangs des tâches F, G et H est dû seulement au changement des prédécesseurs de la tâche E.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0075-00.png]]

_**Figure 3.10 Construction du graphe PERT de l’exemple n° 2**_ 

**Traçage du diagramme GANTT** 

Le diagramme GANTT est une représentation linéaire, dont la méthodologie de construction diffère de celle par réseau présentée cidessus. Ce diagramme ne dépend pas des rangs d’enclenchement des tâches mais des types de liaisons et de la durée d’exécution des tâches. 

Pour présenter la méthodologie de la construction du planning GANTT, on reprend les données de l’exemple n° 1 du **tableau [3.8](20_3.8_représentation_matricielle.md)** . On y ajoute une colonne indiquant la durée de réalisation de chaque tâche (voir **tab. [3.12](24_3.12_application_3-3.md)** ). Comme déjà indiqué, le diagramme GANTT est modélisé sous la forme d’un tableau dont les lignes représentent

_**Tableau [3.12](24_3.12_application_3-3.md) Tableau des tâches avec indication des durées d’exécution de l’exemple n° 1**_ 

|**Activité**|**Prédécesseur**|**Durée (j)**|
|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A_<br>_B_<br>_C ; F_<br>_A_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_5_<br>_3_<br>_15_<br>_6_<br>_4_<br>_18_<br>_14_<br>_14_<br>_5_|

Pour tracer le diagramme GANTT, on procède de la manière suivante : 

1. Dresser un tableau avec les tâches en ligne et les jours en colonne (voir **fg. [3.11](23_3.11_application_3-2.md)** ). 

2. Tracer des barres aux longueurs égales aux durées des tâches, présentées dans le **tableau [3.12](24_3.12_application_3-3.md)** , selon l’ordre suivant : 

   - commencer par la tâche A, d’une durée de 5 jours. La barre aura une longueur de cinq colonnes ; après la fin de la tâche A commencent deux tâches B et E, de durées et de longueurs différentes. Tracer deux barres qui commencent à partir de la fin de la tâche A et de longueur de 3 colonnes pour la tâche B et de 4 colonnes pour la tâche E ; si une tâche a plus d’un prédécesseur, comme le cas des tâches D et I, on prend le plus long chemin pour commencer la tâche concernée, c’est-à-dire la fin de tous les prédécesseurs ; la tâche D commence après la fin des tâches C et F. La tâche F, d’une durée de 18 jours, se termine après la tâche C de durée 15 jours. Donc la tâche D commence après la fin de la tâche F puisque la tâche C a été déjà terminée ; selon le même principe, terminer de la même manière le traçage des autres tâches. 

3. La construction du diagramme GANTT aboutit à déterminer la durée du projet, sans effectuer de calculs comme dans les autres méthodes.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0077-00.png]]

_**Figure [3.11](23_3.11_application_3-2.md) Construction du diagramme GANTT de l’exemple n° 1**_ 

On procède de la même manière pour la construction du diagramme GANTT de l’exemple n° 2 présenté dans la **fgure [3.12](24_3.12_application_3-3.md)** . On remarque qu’il y a une différence entre les diagrammes, à la suite du changement des prédécesseurs de la tâche E et des successeurs de la tâche A. Dans ce cas, il y a deux tâches initiales A et E et un changement dans la durée du projet et dans le déroulement des tâches ayant des liaisons avec la tâche E.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0078-00.png]]

_**Figure [3.12](24_3.12_application_3-3.md) Construction du diagramme GANTT de l’exemple n° 2**_ 

**Traçage du planning chemin de fer** 

**Principe** 

Le planning chemin de fer est une représentation linéaire des activités répétitives et cycliques d’un travail dans le temps. Le graphe du chemin de fer est formé de deux axes : l’axe des abscisses indique

le temps et l’axe des ordonnées représente généralement les zones de travail, les quantités réalisées ou les distances à parcourir. 

On présente, ci-dessous, le principe de traçage du planning chemin de fer dans le cas de la gestion de production et le cas de la rotation des camions de terrassement. 

**Planning de gestion de production** 

Le planning du type chemin de fer permet de visualiser la cadence de production et la synchronisation des différentes tâches des cycles de préfabrication. Dans un système d’axe formé du nombre d’éléments en ordonnées et du temps en abscisses, on trace les trois courbes suivantes, présentées dans la **fgure 3.13** . 

1. Courbe de pose : elle permet de visualiser le nombre d’éléments posés dans l’ouvrage en fonction du temps. 

2. Courbe de fabrication : elle permet de visualiser le nombre d’éléments préfabriqués dans l’atelier de préfabrication en fonction du temps. 

3. Courbe d’évolution des stocks : pour déterminer le stock d’éléments préfabriqués, on trace cette courbe par déduction des deux courbes précédentes.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0080-00.png]]

_**Figure 3.13 Courbes de production**_ 

**Planning de rotation des camions de terrassement** 

L’élaboration du planning de rotation des camions de terrassement a pour objectif d’optimiser l’utilisation des matériels de manière à déplacer le maximum de terre possible en un minimum de temps. Autrement dit, il faut éviter de perdre du temps en attendant les camions de transport de terre ou l’engin de terrassement, pour avoir un travail sans interruption. Dans le cas du terrassement en déblai, le cycle de travail est formé de quatre opérations répétitives des camions (voir **fg. 3.14** ). 

1. Le chargement des déblais sur chantier. 

2. L’aller en charge vers la décharge. 

3. Le déchargement du déblai. 

4. Le retour vide vers le chantier **.**
