---
type: document-section
document_id: cct-105
section_id: doc105-tech-0169
ordre_document: 192
titre: ARTICLE C16. PAR. 5. Caractéristiques de fonctionnement
aliases:
  - CCT 105 — HVAC FR 2023 — 192 ARTICLE C16. PAR. 5. Caractéristiques de fonctionnement
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/191-article-c16-par-4-essais|ARTICLE C16. PAR. 4. Essais]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/193-article-c16-par-6-clauses-techniques|ARTICLE C16. PAR. 6. Clauses techniques]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 192_article_c16._par._5._caractéristiques_de_fonctionnement.md
created: 2026-04-28
updated: 2026-04-28
contextes:
  - appel-doffres
  - execution-projet
  - technique
autorite:
  - contractuel
juridictions:
  - belgique
familles_sources:
  - contrat
---

#### ARTICLE C16. PAR. 5. CARACTÉRISTIQUES DE FONCTIONNEMENT 

**1. Pression différentielle du filtre** 

Un filtre est toujours choisi dans la classe qui convient le mieux à l’application prévue. Au fur et à mesure que l’efficacité augmente, le filtre retient plus de particules mais la pression différentielle initiale augmente. En conséquence, la puissance du ventilateur requise augmente également. 

Dans un souci d’économie d’énergie, la pression différentielle initiale ∆pi et la pression différentielle finale ∆pf du filtre en utilisation ne peuvent dépasser les valeurs indiquées dans le tableau suivant : 

|Classe de filtre|Pression différentielle<br>initiale maximale au<br>débit de service<br>∆pi,max(Pa)|Pression différentielle finale<br>maximale au débit de service<br>∆pf, max(Pa)|
|---|---|---|
|Grossier <50%|40|∆pi+ 50 Pa|
|Grossier ≥50%|50||
|_e_PM10 50%|60||
|_e_PM2,5 50%|80|∆pi+ 100 Pa|
|_e_PM1 50%|90||
|_e_PM1 60%|100||
|_e_PM170%|110||
|_e_PM1 80%|120||
|E10 à E12|250|2 x∆pi|
|H13 à U17|selonétude spécifique||



Tableau C16.5.-1 : Pression différentielle admissible des filtres à air. 

Remarques : 

- Le débit de service est toujours inférieur ou égal au débit d’essai du filtre. 

- Si le procès-verbal d’essai d’un filtre ne mentionne pas la pression différentielle initiale au débit de service, on détermine celle-ci en admettant que la pression différentielle initiale varie proportionnellement en fonction du débit. 

La pression différentielle finale conditionne le remplacement du filtre. La valeur retenue est au maximum celle indiquée ci-dessus dans le tableau C.16.5.-1, sans dépasser celle indiquée par le fabricant dans sa documentation technique. 

Un capteur de pression différentielle est installé au niveau du filtre. Le régulateur signale un défaut lorsque la pression différentielle finale (valeur paramétrable) est dépassée. La pression différentielle peut également être lue localement, soit par un manomètre différentiel, soit par un affichage numérique sur le capteur de pression différentielle. Le signal de défaut est transmis au système de gestion ou, si aucun système de gestion n’est prévu, via une LED rouge sur le tableau électrique dont dépend le caisson de traitement d’air. La valeur mesurée et la valeur maximale paramétrée sont transmises au système de régulation si un tel système est présent. 

Les dispositions ci-dessus ne s'appliquent pas aux filtres des unités terminales et des bouches de ventilation. 

Dans le cas d’un filtre à deux étages dans un caisson de traitement d’air (préfiltre et filtre principal), un capteur de pression différentielle et une alarme en cas de dépassement de la valeur finale réglée sont prévus séparément pour les deux étages de filtration. 

Les prises de pression sont autant que possible localisées dans des zones où le flux d’air est uniforme.

**2. Durée de vie du filtre / aspects énergétiques** 

**2.1. Généralités** 

Les filtres sont remplacés au plus tard lorsque la pression différentielle finale ou la durée d’utilisation hygiénique est atteinte. 

S’il y a un étage unique de filtration, le filtre est remplacé au moins chaque année pour des raisons d’hygiène. Lorsque la filtration comporte deux étages, le préfiltre est remplacé au moins chaque année, le filtre principal au moins tous les deux ans. 

La durée de vie du filtre dépend également fortement de la qualité d’air aspiré. Il est donc important de localiser l’admission d’air extérieur d’un groupe de traitement d’air dans une zone peu polluée (voir également art B4. PAR2). 

**2.2. Groupe ISO grossier** 

Afin de garantir une capacité de colmatage et une durée de vie suffisantes, la surface développée du médium filtrant des filtres à poches du groupe ISO grossier est au moins égale à 10 m² par 1 m² de surface frontale nette du filtre. 

**2.3. Groupes ISO e**_ **PM** 

Les filtres des groupes ISO _e_ PM sont certifiés Eurovent. Ils sont au minimum de **classe d’efficacité énergétique A selon la certification Eurovent** applicable au moment du dépôt de l’offre. Les informations relatives à la certification Eurovent du filtre (avec référence datée) ainsi qu’à sa classe d’efficacité énergétique et son débit d’essai sont clairement indiquées sur le filtre ou son emballage, ou à défaut dans la documentation technique jointe (fiche technique et dossier as-built). 

Dans certains cas particuliers, le recours à des filtres de classe énergétique B est autorisé, moyennant approbation préalable du [[concepts/fonctionnaire-dirigeant|Fonctionnaire Dirigeant]]. Cela peut être par exemple dans le cas d’une rénovation ou remplacement d’une installation, s’il n’est pas possible d’aménager une section de filtration de taille suffisante pour accueillir un filtre de classe énergétique A, ou pour des installations ne fonctionnant qu’un nombre limité (≤1000) d’heures par an. 

Remarques : 

- Le tableau ci-dessous reprend pour information les exigences relatives à la consommation annuelle d’énergie établie selon la recommandation Eurovent 4/21-2019 pour les classes les plus courantes prescrites par le présent article : 

|**Classe**<br>**ISO 16890**|**_e_PM10 50%**|**_e_PM2,5 50%**|**_e_PM1 50%**|**_e_PM1 60%**|**_e_PM1 70%**|**_e_PM1 80%**|
|---|---|---|---|---|---|---|
|Eurovent<br>A+|≤ 450 kWh|≤ 700 kWh|≤ 800 kWh|≤ 850 kWh|≤ 950 kWh|≤ 1050 kWh|
|Eurovent A|≤550 kWh|≤800 kWh|≤900 kWh|≤950 kWh|≤1100 kWh|≤1250 kWh|
|Eurovent B|≤650 kWh|≤950 kWh|≤1050 kWh|≤1100 kWh|≤1250 kWh|≤1450 kWh|



Tableau C16.5.-2 : Classification Eurovent des filtres à air. 

- Pour les filtres compacts, vu leur capacité de colmatage plus faible et de manière à garantir une bonne durée de vie, il est de plus imposé une surface minimale de medium filtrant de 5 m² par 1000 m³/h de débit de service. 

**2.4. Groupes E, H et U** 

Pour ces groupes de filtres, le cahier spécial des charges précise les conditions relatives à la sélection de la taille du filtre en regard de l’application particulière considérée.
