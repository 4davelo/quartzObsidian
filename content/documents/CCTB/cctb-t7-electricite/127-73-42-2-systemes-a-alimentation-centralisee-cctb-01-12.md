---
type: document-section
document_id: cctb-t7-electricite
section_id: "section:73.42.2"
ordre_document: 127
titre: "73.42.2 Systèmes à alimentation centralisée CCTB 01.12"
aliases: [CCTB T7 — Électricité 01.13 — 127 73.42.2 Systèmes à alimentation centralisée CCTB 01.12]
resume_section: |-
  **73.42.2 Systèmes à alimentation centralisée CCTB 01.12**

  **Description générale :**
  Fourniture, pose et câblage de luminaires d'éclairage de sécurité à alimentation centralisée, alimentés par une batterie centralisée. Le câblage est distinct du reste de l'installation. Conformité au RGIE et à la norme [NBN EN 50172]. Surveillance centralisée via écran ou TCP-IP.

  **73.42.2a Sources d'alimentation centralisée :**
  Centrale avec batteries (sans entretien, norme [NBN EN 50171]), chargeur, modules de commande et surveillance. Programmation des fonctions "permanent", "non-permanent" ou commutée. Tensions : 230 V AC (normal), 230 V DC (secours). Autonomie par défaut : 1h.

  **73.42.2b Luminaires d'évacuation sans signalisation :**
  LED ≥ 150 lm, température 4000/6500 K, durée de vie jusqu'à 100000 h. Pose : encastrée, apparente, suspendue, etc. Indices IP21/42 (par défaut) et IK03/04 (par défaut). Adressage possible.

  **73.42.2c Luminaires d'évacuation avec signalisation :**
  Caractéristiques identiques aux luminaires sans signalisation.

  **73.42.2d Luminaires anti-panique :**
  LED ≥ 100 lm, température 4000/6500 K, durée de vie jusqu'à 100000 h. Pose et indices similaires aux luminaires d'évacuation. Assurent visibilité et sécurité vers les chemins d'évacuation.

  **73.42.2e Luminaires pour travaux dangereux :**
  LED ≥ 400 lm (par défaut), température 4000/6500 K, durée de vie jusqu'à 100000 h. Conformes à [NBN EN 1838], garantissent la sécurité dans les environnements dangereux. Pose et indices similaires aux autres luminaires.

  **Mesurage :**
  Unité : pièce (pc). Nature du marché : QF/QP selon le type.
  - **73.42.2a Systèmes à alimentation centralisée - sources d'alimentation centralisée CCTB 01.11** — `section:73.42.2a`, article, profondeur 6, pages 230-230
  - **73.42.2b Systèmes à alimentation centralisée - luminaires d'éclairage d'évacuation sans signalisation CCTB 01.12** — `section:73.42.2b`, article, profondeur 6, pages 230-230
  - **73.42.2c Systèmes à alimentation centralisée - luminaires d'éclairage d'évacuation avec signalisation CCTB 01.12** — `section:73.42.2c`, article, profondeur 6, pages 231-231
  - **73.42.2d Systèmes à alimentation centralisée - luminaires d'éclairage anti-panique CCTB 01.12** — `section:73.42.2d`, article, profondeur 6, pages 232-232
  - **73.42.2e Systèmes à alimentation centralisée - luminaires d'éclairage de sécurité des emplacements de travaux dangereux CCTB 01.12** — `section:73.42.2e`, article, profondeur 6, pages 232-232
document_parent: "[[documents/CCTB/cctb-t7-electricite/index|CCTB T7 — Électricité 01.13 — Index]]"
section_precedente: "[[documents/CCTB/cctb-t7-electricite/126-73-42-1-systemes-autonomes-cctb-01-11|73.42.1 Systèmes autonomes CCTB 01.11]]"
section_suivante: "[[documents/CCTB/cctb-t7-electricite/128-73-5-cctb-01-02|73.5 CCTB 01.02]]"
tags: [document-section, cctb]
sources: [127_73.42.2_systèmes_à_alimentation_centralisée_cctb_01.12.md]
created: 2026-04-28
updated: 2026-04-28
contextes: [appel-doffres, execution-projet, technique]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
---

##### 73.42.2 Systèmes à alimentation centralisée [[entities/cctb|CCTB]] 01.12 

**DESCRIPTION** 

**Définition / Comprend** 

Il s'agit de la fourniture, la pose et le câblage des luminaires d'éclairage de sécurité à alimentation centralisée et de leur(s) source(s) d'alimentation. L'alimentation de secours est fournie à partir d’une batterie centralisée. Le câblage des luminaires de sécurité est indépendant du câblage du reste de l'installation des luminaires. 

L'installation d'une source centrale répond strictement au [[concepts/rgie|RGIE]] (notamment au 4.3.3). 

Plusieurs appareils d'éclairages sont connectés sur la même source d'énergie. Lors d'un défaut de secteur, l'armoire d'alimentation centralisée commute sur l'alimentation électrique de secours. La lecture de l'état des luminaires se fait par détection : de ligne / individuelle en un point central. Cela se fait via : un écran clair dans l'armoire d'alimentation centrale / via TCP-IP (à distance). 

**DOCUMENTS DE RÉFÉRENCE** 

**Matériau** 

[NBN EN 50172, Systèmes d'éclairage de sécurité] 

**Exécution** 

[NBN EN 50172, Systèmes d'éclairage de sécurité]

###### 73.42.2 a Systèmes à alimentation centralisée - sources d'alimentation centralisée [[entities/cctb|CCTB]] 01.11 

**DESCRIPTION** 

**Définition / Comprend** 

Il s'agit de la fourniture, la pose et le câblage de sources d'alimentation centralisée. La source d'alimentation centralisée est une centrale possédant l'électronique et les batteries nécessaires à l'alimentation des luminaires de sécurité. La source alimente exclusivement les luminaires de sécurité. 

**Fonctionnement :** 

- En fonctionnement normal, les luminaires sont alimentés par le réseau 230 V AC. 

- En fonctionnement 'secours' tous les luminaires raccordés sont alimentés en 230 V DC lors d’une coupure de courant totale et en 230 V AC par l'intermédiaire d'un module d'inversion. Cette inversion est activée par un contrôleur de phases, par un module externe inverse ou par un contact auxiliaire placé sur des disjoncteurs d'éclairage généraux se trouvant dans des zones où se trouvent des éclairages de sécurité non permanent. 

La source d'alimentation centralisée inclut les éléments qui suivent : 

- Un ensemble de batteries groupées conformément à la norme [NBN EN 50171], dont le rôle est d'alimenter et contrôler les luminaires de sécurité de façon centrale. Pour ce qui est des batteries au plomb, celles-ci sont "sans entretien". 

- Une alimentation 

- Une armoire 

- Un chargeur conçu de telle manière qu'après décharge complète, les batteries retrouvent 80 % de leur charge en 12 heures. 

- Module de commande et de programmation 

- Modules d'alimentation et de surveillance individuelle des luminaires (maximum 20 luminaires par circuit). 

- Module web (en option) 

Rajouter : Programmation Permanent / Non permanent 

Spécifications électriques 

Les fonctions "permanent", "non-permanent" ou commutée sont programmables à partir de la centrale. Il est possible de programmer sur la même ligne des fonctions différentes, ce qui permet une réduction de la quantité de câblage. Tension nominale : 230 V AC 

- Tension de sortie en état normal : 230 V AC 

- Tension de sortie en état secours : 230 V DC 

- Autonomie : 1 heure (par défaut) / ***, à une température de 21 °C 

**MESURAGE** 

**unité de mesure:** 

pc 

**nature du marché:** 

**QF** 

###### 73.42.2 b Systèmes à alimentation centralisée - luminaires d'éclairage d'évacuation sans signalisation [[entities/cctb|CCTB]] 01.12 

**DESCRIPTION** 

**Définition / Comprend**

Ce poste inclut la pose, la fourniture, et le câblage de luminaires d'éclairages d'évacuation sans signalisation. 

**MATÉRIAUX** 

**Caractéristiques générales** 

- Flux lumineux : ≥ 150 lm 

- Source lumineuse : LED 

- Température de la lumière : 4000 / 6500 K 

- Durée de vie : 30000 / 50000 / 70000 / 100000 h 

- Mode de pose du luminaire : encastré ou semi-encastré / apparent (par défaut) / suspendu / en drapeau / *** 

- Surface de pose : plafond (par défaut) / mur / *** 

- Indice de protection IP : IP 21 / 42 (par défaut) / 44 / 55 / 65 / *** 

- Indice de protection Ik : IK 03 / 04 (par défaut) / 09 / *** 

- Adressage : Oui / Non 

**MESURAGE** 

**unité de mesure:** 

**pc** 

**nature du marché:** 

**QP** 

###### 73.42.2 c Systèmes à alimentation centralisée - luminaires d'éclairage d'évacuation avec signalisation [[entities/cctb|CCTB]] 01.12 

**DESCRIPTION** 

**Définition / Comprend** 

Ce poste inclut la pose, la fourniture, et le câblage de luminaires d'éclairages d'évacuation sans signalisation. 

**MATÉRIAUX** 

**Caractéristiques générales** 

- Flux lumineux : ≥ 150 lm 

- Source lumineuse : LED 

- Température de la lumière : 4000 / 6500 K 

- Durée de vie : 30000 / 50000 / 70000 / 100000 h 

- Mode de pose du luminaire : encastré ou semi-encastré / apparent (par défaut) / suspendu / en drapeau / *** 

- Surface de pose : plafond (par défaut) / mur / *** 

- Indice de protection IP : IP 21 / 42 (par défaut) / 44 / 55 / 65 / *** 

- Indice de protection IK : IK 03 / 04 (par défaut) / 09 / *** 

- Adressage : Oui / Non 

**MESURAGE** 

**unité de mesure:** 

**pc** 

**nature du marché:** 

QP

###### 73.42.2 d Systèmes à alimentation centralisée - luminaires d'éclairage anti-panique [[entities/cctb|CCTB]] 01.12 

**DESCRIPTION** 

**Définition / Comprend** 

Il s'agit de la fourniture et de l'installation de luminaire anti panique dont la fonction est de réduire le risque de panique et de permettre un déplacement en sécurité vers le chemin d'évacuation des personnes présentes, et ce en assurant une visibilité et une illumination adéquates du chemin d'évacuation. 

**MATÉRIAUX** 

**Caractéristiques générales** 

- Flux lumineux : ≥ 100 lm 

- Source lumineuse : LED 

- Température de la lumière : 4000 / 6500 K 

- Durée de vie : 30000 / 50000 / 70000 / 100000 h 

- Mode de pose du luminaire : encastré ou semi-encastré / apparent (par défaut) / suspendu / en drapeau / *** 

- Surface de pose : plafond (par défaut) / mur / *** 

- Indice de protection IP : IP 21 / 42 (par défaut) / 44 / 55 / 65 / *** 

- Indice de protection IK : IK 03 / 04 (par défaut) / 09 / *** 

- Adressage : Oui / Non 

**MESURAGE** 

**unité de mesure:** 

pc 

**nature du marché:** 

QP 

###### 73.42.2 e Systèmes à alimentation centralisée - luminaires d'éclairage de sécurité des emplacements de travaux dangereux [[entities/cctb|CCTB]] 01.12 

**DESCRIPTION** 

**Définition / Comprend** 

Il s'agit de la fourniture et de l'installation de luminaires d'éclairage de sécurité des emplacements de travaux dangereux défini suivant la norme [NBN EN 1838] comme l'éclairage de sécurité prévu pour garantir la sécurité des personnes occupées à des activités potentiellement dangereuses ou travaillant dans un environnement dangereux et permettant le bon déroulement des procédures d'arrêt pour la sécurité de l'opérateur et des autres occupants des locaux. 

**MATÉRIAUX** 

**Caractéristiques générales** 

- Flux lumineux : ≥ 400 (par défaut) / *** lm 

- Source lumineuse : LED 

- Température de la lumière : 4000 / 6500 K 

- Durée de vie : 30000 / 50000 / 70000 / 100000 h 

- Mode de pose du luminaire : encastré ou semi-encastré / apparent (par défaut) / suspendu / en drapeau / *** 

- Surface de pose : plafond (par défaut) / mur / ***

- Indice de protection IP : IP21/ 42 (par défaut) / 44 / 55 / 65 / *** 

- Indice de protection IK : IK03 / 04 (par défaut) / 09 / *** 

- Adressage : Oui / Non 

**MESURAGE** 

**unité de mesure:** 

pc 

**nature du marché:** 

QP
