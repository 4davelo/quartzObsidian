---
aliases: ["Mise à la Terre et Équipotentialité"]
tags: [concept, electricite, terre, equipotentialite, foudre, hvac, sécurité]
sources: [T7 Electricité CCTB 01.13_20260317.pdf]
created: 2026-04-22
updated: 2026-04-29
contextes: [technique, appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
disciplines: [cvc, electricite]
---
# Mise à la Terre et Équipotentialité

## Définition

Dans le tome T7, la mise à la terre couvre l'électrode, le conducteur de terre, la barrette de sectionnement, le conducteur de protection principal, la borne principale de terre, les liaisons équipotentielles et les conducteurs de protection individuels de chaque circuit.

## Ce que T7 impose

Le tome impose une lecture complète de la terre du bâtiment :

- une électrode de terre, typiquement boucle de fondation ou électrodes individuelles ;
- une barrette de sectionnement permettant la mesure ;
- une borne principale de terre ;
- un conducteur de protection principal ;
- des liaisons équipotentielles principales ;
- des liaisons équipotentielles supplémentaires en locaux humides ;
- un conducteur de protection individuel pour chaque circuit, vers chaque prise, point lumineux ou point de connexion.

Le schéma de liaison à la terre est à choisir conformément au [[concepts/rgie|RGIE]] parmi `TT`, `TN`, `TN-S`, `TN-C-S`, `TN-C` ou `IT`, en courant alternatif comme en courant continu.

## Impact direct sur le HVAC

Pour les techniques HVAC, cette matière n'est pas abstraite. Elle touche :

- les groupes frigorifiques ;
- les pompes à chaleur ;
- les ventilateurs, pompes et équipements de local technique ;
- les chauffe-eau et équipements sanitaires ;
- les cadres et structures métalliques des panneaux photovoltaïques ;
- les conduites métalliques fixes accessibles ;
- les radiateurs et appareils en salles d'eau.

Les liaisons équipotentielles principales doivent relier la borne principale aux parties métalliques fixes accessibles, notamment les conduites principales de gaz, d'eau et de chauffage central.

En salles de bains et douches, T7 impose en plus des liaisons équipotentielles supplémentaires entre parties métalliques, radiateurs, conduites, chauffe-eau et conducteurs de protection.

## Lien avec le photovoltaïque et la foudre

Le chapitre photovoltaïque de T7 précise que les cadres métalliques des modules et leurs structures doivent être mis à la terre suivant le [[concepts/rgie|RGIE]], avec un conducteur de terre de section adaptée.

Le tome renvoie aussi à la série `NBN EN 62305` pour les installations de paratonnerre. Pour un bâtiment technique, cela relie directement :

- protection foudre ;
- protection surtension ;
- mise à la terre des structures ;
- sécurité des équipements sensibles ;
- cohabitation entre solaire, HVAC et enveloppe.

## Importance pratique

En marché public, la terre et l'équipotentialité ne peuvent pas être traitées comme un simple détail d'exécution électrique. Elles conditionnent la conformité `RGIE`, la sécurité des personnes, la robustesse des équipements HVAC et la cohérence entre protections surtension, panneaux photovoltaïques et techniques spéciales.

## Pages liées

- [[sources/cctb-t7-electricite|CCTB T7 - Électricité]]
- [[concepts/rgie|RGIE]]
- [[concepts/electricite-et-interfaces-hvac|Électricité et Interfaces HVAC]]
- [[concepts/installations-solaires-en-toiture|Installations Solaires en Toiture]]
- [[concepts/production-de-chaleur|Production de Chaleur]]
- [[concepts/climatisation-et-froid|Climatisation et Froid]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
