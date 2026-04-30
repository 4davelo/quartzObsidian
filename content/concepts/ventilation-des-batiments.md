---
aliases:
- Ventilation des Bâtiments
tags:
- concept
- ventilation
- peb
- qualité-air
- hvac
- bâtiments
sources:
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
- T1 Terrassements _ fondations CCTB 01.13_20260317.pdf
- T2 Superstructures CCTB 01.13_20260317.pdf
- T3 Travaux de toiture CCTB 01.13_20260317.pdf
- T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf
- T5 Fermetures _ Finitions intérieures CCTB 01.13_20260317.pdf
- T6 HVAC - sanitaires CCTB 01.13.pdf
- CCT105TB FR 2023.pdf
- Note info_CTI_HVAC_26-1_ventilation_des_lieux_de_travail_2021.pdf
- La Technique du bâtiment – Tous corps d’état.epub
created: 2026-04-22
updated: 2026-04-29
contextes:
- technique
- appel-doffres
autorite:
- contractuel
juridictions:
- wallonie
- bruxelles
- belgique
familles_sources:
- cctb
- contrat
- guide
disciplines:
- cvc
- enveloppe
---
# Ventilation des Bâtiments

## Définition

Dans le tome T6, la ventilation est l'apport et l'enlèvement d'air voulus par conception à et depuis un espace à traiter. Elle couvre à la fois la logique de système, les groupes de production, les réseaux, les organes de transfert, les hottes, les tests et la régulation, en résidentiel comme en non-résidentiel.

## Cadre réglementaire

T6 rattache explicitement la ventilation à la [[concepts/peb|réglementation PEB]]. La majorité des travaux soumis à permis d'urbanisme en construction, rénovation ou changement d'affectation exigent l'installation d'un système de ventilation complet ou partiel.

Les textes centraux sont :

- `NBN D 50-001` pour le résidentiel ;
- `NBN EN 16798-1` et `NBN EN 16798-3` pour le non-résidentiel ;
- la loi du `2022-11-06` pour les lieux fermés accessibles au public ;
- `NIT 258` pour la conception pratique des systèmes résidentiels.

Le [[entities/cct-105|CCT 105]] complète cette lecture par des exigences de conception non résidentielles, notamment la [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/43-article-b1-par-4-qualite-de-l-air-interieur|qualité d'air intérieur]], les [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/55-article-b4-exigences-generales-de-conception-des-installations-de-ventilation|exigences générales de ventilation]] et les objectifs énergétiques de [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/62-article-b5-exigences-dans-le-domaine-de-l-utilisation-rationnelle-de-l-energie|l'article B5]].

## Systèmes A, B, C et D

Pour le résidentiel, T6 reprend les quatre systèmes issus de `NBN D 50-001` :

- `A` : alimentation naturelle et évacuation naturelle ;
- `B` : alimentation mécanique et évacuation naturelle ;
- `C` : alimentation naturelle et extraction mécanique ;
- `D` : alimentation mécanique et extraction mécanique.

Ces systèmes sont décrits comme des combinaisons cohérentes entre amenées d'air, ouvertures de transfert, équipements de production, bouches terminales et rejets. T6 rend aussi plus explicite la différence entre versions individuelles, collectives et parfois décentralisées du système.

## Débits nominaux résidentiels

T6 reprend les règles de base suivantes :

- séjour : `3,6 m³/h/m²` avec un minimum de `75 m³/h` ;
- chambres, bureaux, salles de jeu : `3,6 m³/h/m²` avec un minimum de `25 m³/h` ;
- cuisines, salles de bains, buanderies et locaux analogues : `3,6 m³/h/m²` avec un minimum de `50 m³/h` ;
- cuisine ouverte : minimum `75 m³/h` ;
- WC : `25 m³/h`.

## Contraintes de conception

T6 insiste sur plusieurs points :

- les locaux desservis, les sens de flux et les débits doivent être explicités par local ;
- les appareils à combustion ouverte ne peuvent pas être perturbés par la ventilation ;
- les appareils à combustion ouverte d'une puissance `>= 10 kW` sont interdits dans les pièces d'habitation et petits débarras en communication avec la cuisine ;
- pour le système `D`, la récupération de chaleur occupe une place structurante, avec des exigences de rendement et de maintenance.

Les chapitres `61.1` et `61.2` ajoutent des contraintes plus opérationnelles :

- le système doit rester conforme aux normes en vigueur au moment réel de la mise en oeuvre ;
- les débits minimums et le sens de flux doivent être précisés pour chaque local, pas seulement pour le bâtiment dans son ensemble ;
- la puissance spécifique `SFP` et les hypothèses de débits recommandés sont utilisées comme paramètres de conception ;
- l'implantation du groupe doit permettre l'entretien des filtres, ventilateurs, répartiteurs et évacuations de condensats.

## Lieux de travail

Pour les locaux de travail, la [[concepts/ventilation-des-lieux-de-travail|Ventilation des lieux de travail]] impose une vérification séparée. La note CTI 26-1 articule les exigences de `CO2`, d'humidité relative et d'analyse de risques avec les débits de conception du CCT 105. La section [[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-26-1-ventilation-lieux-travail/35-debit-d-air-a-prevoir|Débit d'air à prévoir]] maintient les débits CCT 105 pour certains locaux, mais impose `40 m³/h` par personne pour les lieux de travail sans conditions de dérogation.

## Groupes de production et récupération

Le chapitre `61.2` montre que la ventilation ne se résume pas à un système `A/B/C/D` abstrait. Le CCTB distingue notamment :

- caissons de ventilation pour habitat individuel ou collectif ;
- systèmes `C` collectifs avec bouches, capteurs et clapets pilotés ;
- systèmes `D` individuels, collectifs ou décentralisés ;
- récupérateurs de chaleur ;
- caissons de traitement d'air pour les cas plus complexes ;
- niveaux de filtration et options de batteries de pré ou post-chauffage.

Pour les systèmes `D`, le tome insiste sur l'évacuation correcte des condensats, le rendement de récupération, le nombre de vitesses, les capteurs éventuels `CO2 / humidité / COV` et l'accessibilité des organes de maintenance.

## Interfaces enterrées et structurelles

Les tomes T1 et T2 complètent cette vision en montrant que la ventilation commence parfois avant l'entrée dans le bâtiment et qu'elle se prolonge ensuite dans les superstructures. Ils encadrent notamment :

- les éléments de ventilation nécessaires aux caves et vides sanitaires dans les travaux de raccordements utilitaires ;
- les traversées de murs, fondations et dalles pour conduites et amenées d'air ;
- les exigences de continuité coupe-feu lorsque ces traversées concernent des parois résistantes au feu ;
- les [[concepts/puits-canadiens-a-air|Puits Canadiens à Air]], avec prises d'air, conduits enterrés, regards de visite et évacuation des condensats ;
- l'étanchéité au droit des dalles sur sol et, selon le cas, les barrières au radon qui influencent aussi la performance globale de l'enveloppe.

T2 ajoute la partie visible et structurelle de cette interface :

- les éléments de ventilation intégrés à la maçonnerie, comme les gaines télescopiques de ventilation pour vides sanitaires ou caves, les soupiraux et certains blocs de verre ventilants ;
- les conduits de ventilation maçonnés, y compris leurs accessoires, leur isolation et leurs recueils de condensats ;
- les percements et fourreaux à anticiper dans le gros-oeuvre ;
- les pénétrations de toiture avec continuité de l'étanchéité à l'eau en surface et de l'étanchéité à l'air côté chaud.

La ventilation est donc liée à [[concepts/terrassements-et-fondations|Terrassements et Fondations]] et aux [[concepts/superstructures|Superstructures]] dès qu'elle implique une prise d'air enterrée, une gaine maçonnée, une traversée structurelle ou un raccordement à l'enveloppe.

Le tome T3 précise ensuite la lecture côté toiture :

- les sous-toitures doivent intégrer les réservations pour traversées techniques et les découpes autour des équipements ;
- les manchons et raccords d'étanchéité à l'air sont explicitement prévus pour les conduits et câbles traversant le complexe de toiture ;
- les lanterneaux, coupoles et exutoires occupent la toiture et imposent une coordination d'implantation avec les prises et rejets d'air ;
- les détails d'évacuation des eaux autour des émergences doivent rester cohérents avec le réseau de ventilation en toiture.

Le tome T4 ouvre ensuite le volet façade de cette même logique :

- les [[concepts/ouvertures-de-ventilation-en-facade|Ouvertures de Ventilation en Façade]] sont traitées comme des composants d'enveloppe intégrés dans le mur, la baie, la quincaillerie, le vitrage ou le profil de châssis ;
- leur sélection se fait sur le débit nominal sous `2 Pa` conformément à `NBN D 50-001` ;
- T4 rappelle qu'en logements et rénovations importantes, l'insuffisance de ventilation combinée à une enveloppe mal traitée accroît les risques de condensation superficielle et de moisissures ;
- en zone bruyante, l'amenée d'air doit aussi satisfaire à une performance acoustique adaptée, ce qui lie directement ventilation et façade acoustique.

La ventilation est donc liée non seulement à [[concepts/terrassements-et-fondations|Terrassements et Fondations]], [[concepts/superstructures|Superstructures]] et [[concepts/travaux-de-toiture|Travaux de Toiture]], mais aussi à [[concepts/fermetures-et-finitions-exterieures|Fermetures et Finitions Extérieures]] dès qu'elle s'appuie sur la façade pour l'air neuf ou pour certains rejets.

Le tome T5 ferme ensuite la boucle côté intérieur :

- les [[concepts/menuiseries-interieures-et-transferts-dair|Menuiseries Intérieures et Transferts d'Air]] définissent les ouvertures de transfert, grilles de porte, grilles de paroi et détalonnages suivant la logique `NBN D 50-001` sous `2 Pa` ;
- les [[concepts/faux-plafonds-et-plafonds-climatiques|Faux-plafonds et Plafonds Climatiques]] reçoivent les éléments de ventilation et imposent un séquençage avec les lots techniques en plénum ;
- les [[concepts/planchers-interieurs-techniques|Planchers Intérieurs Techniques]] peuvent intégrer grilles, boitiers, passes-câbles et autres accessoires liés aux réseaux ;
- les [[concepts/cloisons-et-doublages-interieurs|Cloisons et Doublages Intérieurs]] et [[concepts/etancheisation-et-isolation-des-parois-interieures|Étanchéisation et Isolation des Parois Intérieures]] règlent acoustique, feu et étanchéité autour des passages intérieurs.

La ventilation dépend donc aussi de [[concepts/fermetures-et-finitions-interieures|Fermetures et Finitions Intérieures]] dès qu'il faut faire circuler l'air entre les locaux, refermer les gaines et intégrer les terminaux dans le second oeuvre.

## Interfaces feu et bâti

T2 rappelle aussi qu'un conduit de ventilation n'est pas seulement un réseau aéraulique. C'est un élément qui traverse des parois soumises à des exigences de résistance au feu, d'acoustique, d'isolation et d'étanchéité.

Il interdit explicitement de brancher des conduits d'évacuation de fumée ou de gaz sur des conduits de ventilation et impose une coordination étroite avec le gros-oeuvre et la toiture pour les gaines et pénétrations.

## Importance pour un lot HVAC

Pour une réponse à un marché public, la ventilation ne se résume pas au choix d'une machine. Il faut démontrer la cohérence entre système, débits, qualité d'air, acoustique, essais, régulation, accès d'entretien, gestion des condensats, transfert intérieur et compartimentage feu. C'est ce qui fait du chapitre `61` le noyau du volet aéraulique du [[concepts/csc|CSC]].

## Voir aussi

- [[concepts/ventilation-des-lieux-de-travail|Ventilation des lieux de travail]] — règles CO2 et humidité pour locaux de travail.
- [[concepts/qualite-de-lair-interieur|Qualité de l'Air Intérieur]] — objectif de performance de la ventilation.
- [[concepts/distribution-et-regulation-de-ventilation|Distribution et Régulation de Ventilation]] — réseaux, régulation et essais.
- [[concepts/dimensionnement-hvac|Dimensionnement HVAC]] — calcul des débits et conduits.
