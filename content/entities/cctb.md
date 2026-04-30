---
aliases: ["CCTB"]
tags: [entité, norme, cctb, wallonie, spécifications]
sources: [T0 Entreprise _ Chantier CCTB 01.13_20260317.pdf, A Clauses administratives CCTB 01.13_20260317.pdf, T2 Superstructures CCTB 01.13_20260317.pdf, T5 Fermetures _ Finitions intérieures CCTB 01.13_20260317.pdf, T6 HVAC - sanitaires CCTB 01.13_20260317.pdf, CCT105TB FR 2023.pdf]
created: 2026-04-22
updated: 2026-04-28
contextes: [appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
---

# CCTB

**Nom complet :** Cahier des Charges Type Bâtiments  
**Édition actuelle :** 01.13 du 17/03/2026  
**Éditeur :** [[entities/ediwall|Ediwall]] pour le [[entities/service-public-de-wallonie|Service Public de Wallonie]]  
**Site officiel :** <https://batiments.wallonie.be>

## Description

Le CCTB est le cadre de spécification standard pour la construction de bâtiments en Wallonie et en Fédération Wallonie-Bruxelles. Il constitue un langage commun entre pouvoirs adjudicateurs, auteurs de projet et entreprises.

Le CCTB n'est cependant **pas universel à Bruxelles** : les maîtres d'ouvrage fédéraux (Régie des Bâtiments, Défense, SPF) utilisent généralement le [[entities/cct-105|CCT 105]] comme référentiel principal. À Bruxelles, le référentiel applicable dépend donc du type de pouvoir adjudicateur — vérifier le [[concepts/csc|CSC]] est toujours nécessaire.

La distinction pratique est détaillée dans [[concepts/cctb-vs-cct-105-pour-soumissions-hvac|CCTB vs CCT 105 pour Soumissions HVAC]] : le CCTB structure les marchés qui l'activent par tomes et index d'articles, tandis que le CCT 105 structure les marchés HVAC fédéraux par cahier type et annexes propres.

Il sert à la fois :

- de référentiel administratif via le tome A ;
- de cadre général de chantier via le tome T0 ;
- de référentiel technique via les tomes spécialisés T1 à T9.

## Structure des tomes

| Tome | Contenu |
| ---- | ------- |
| A | Clauses administratives |
| T0 | Entreprise / Chantier |
| T1 | Terrassements / Fondations |
| T2 | Superstructures |
| T3 | Travaux de toiture |
| T4 | Fermetures / Finitions extérieures |
| T5 | Fermetures / Finitions intérieures |
| T6 | HVAC – Sanitaires |
| T7 | Électricité |
| T8 | Travaux de peinture / Traitements de surface |
| T9 | Abords |
| CDR | Catalogue des documents de référence |

## Place du tome T6

Le tome `T6 HVAC - sanitaires` est le principal tome technique pour les lots HVAC en marchés publics. Il regroupe six ensembles structurants :

- ventilation ;
- climatisation ;
- chaleur ;
- froid ;
- sanitaires ;
- lutte contre l'incendie liée aux réseaux techniques.

Dans la pratique, c'est le tome à croiser avec le [[concepts/csc|CSC]] dès qu'un lot comporte du chauffage, de la ventilation, de la climatisation, des sanitaires, des PAC, de l'eau chaude sanitaire ou des traversées coupe-feu de réseaux.

## Place du tome T2 pour HVAC

Le tome `T2 Superstructures` ne décrit pas les équipements HVAC eux-mêmes, mais le bâtiment qui les reçoit. Il fixe le cadre des [[concepts/superstructures|Superstructures]] dans lesquelles les techniques doivent être intégrées :

- réservations, percements et fourreaux dans la maçonnerie, le béton, le métal et le bois ;
- conduits maçonnés de fumée et de ventilation ;
- continuité de l'étanchéité à l'eau, de l'étanchéité à l'air, de l'isolation et des performances feu/acoustiques ;
- adaptations de structures existantes pour passages de techniques spéciales.

Dans la pratique, un lot HVAC correctement lu dans le [[entities/cctb|CCTB]] suppose donc presque toujours un croisement entre `T6` pour les équipements et `T2` pour leurs interfaces avec le gros-oeuvre et l'enveloppe.

## Place du tome T5 pour HVAC

Le tome `T5 Fermetures / Finitions intérieures` ne décrit pas les machines HVAC elles-mêmes, mais les ouvrages intérieurs qui les reçoivent et les referment :

- [[concepts/cloisons-et-doublages-interieurs|Cloisons et Doublages Intérieurs]] ;
- [[concepts/etancheisation-et-isolation-des-parois-interieures|Étanchéisation et Isolation des Parois Intérieures]] ;
- [[concepts/planchers-interieurs-techniques|Planchers Intérieurs Techniques]] ;
- [[concepts/faux-plafonds-et-plafonds-climatiques|Faux-plafonds et Plafonds Climatiques]] ;
- [[concepts/menuiseries-interieures-et-transferts-dair|Menuiseries Intérieures et Transferts d'Air]].

Dans la pratique, T5 complète `T2` et `T4` :

- `T2` prépare le support structurel ;
- `T4` ferme l'enveloppe extérieure ;
- `T5` ferme l'interface intérieure du second oeuvre autour des grilles, bouches, plénums, transferts d'air, plafonds climatiques, passages techniques et détails feu / acoustique.

## Système de numérotation

Le CCTB suit une structure hiérarchique à six niveaux :

| Niveau | Subdivision | Index |
| ------ | ----------- | ----- |
| 1 | Tome | A, 0 à 9 |
| 2 | Section | \*0 à \*9 |
| 3 | Titre | \*\*.0 à \*\*.9 |
| 4 | Sous-titre | \*\*.\*0 à \*\*.\*9 |
| 5 | Chapitre | \*\*.\*\*.\*0 à \*\*.\*\*.\*9 |
| 6 | Article | \*\*.\*\*.\*\*.\*a à \*\*.\*\*.\*\*.\*z |

Cette structure permet un référencement précis dans le [[concepts/csc|CSC]] et dans les métrés.

## Utilisation dans un CSC

Un [[concepts/csc|CSC]] bien construit référence les articles du CCTB par leur numéro d'index et ne recopie que les éléments qui exigent des précisions spécifiques au projet.

Pour l'entreprise, cela signifie qu'une grande partie des obligations du marché peut se trouver dans des renvois CCTB plutôt que dans un texte long explicitement réécrit.

## Intérêt pour l'entreprise

Une entreprise qui répond à des marchés publics doit savoir y chercher :

- les conditions de recevabilité de l'offre ;
- les exigences documentaires ;
- les obligations de chantier ;
- les conditions de réception ;
- les points qui impactent la trésorerie, la marge et la responsabilité.

## Voir aussi

- [[concepts/cctb-vs-cct-105-pour-soumissions-hvac|CCTB vs CCT 105 pour Soumissions HVAC]] — distinction de base documentaire pour l'offre HVAC
- [[sources/cctb-t6-hvac-sanitaires|CCTB T6 - HVAC - sanitaires]] — source synthèse du tome technique HVAC
- [[entities/cct-105|CCT 105]] — référentiel HVAC distinct, surtout fédéral
- [[concepts/csc|CSC]] — document qui active la hiérarchie contractuelle
