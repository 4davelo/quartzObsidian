---
aliases:
- Facturation Électronique PEPPOL
tags:
- concept
- facturation
- peppol
- spw
- paiements
- marché-public
sources:
- A Clauses administratives CCTB 01.13_20260317.pdf
created: 2026-04-22
updated: 2026-04-29
contextes:
- appel-doffres
- execution-projet
autorite:
- contractuel
- reglementaire
- reference
juridictions:
- wallonie
- ue
- belgique
phases:
- chantier
- reception
familles_sources:
- cctb
- reglementation
- guide
---
# Facturation Électronique PEPPOL

## Définition

Pour les marchés du [[entities/service-public-de-wallonie|Service Public de Wallonie]], le tome A impose une logique de facturation électronique structurée. Pour une entreprise, ce n'est pas un détail administratif : c'est une condition de bon écoulement des paiements.

## Exigences contractuelles / réglementaires

### Canaux rappelés par le tome A

Le SPW accepte notamment :

- la facturation via un outil comptable connecté au réseau PEPPOL ;
- l'encodage via le portail [[entities/mercurius|Mercurius]].

Identifiants rappelés dans le tome A :

- Scheme ID : 0208
- PEPPOL ID : 0316381138

Un PDF ou un document Word envoyé par email n'est pas considéré comme une facture électronique valable.

La guidance fédérale complète ce tableau :

- l'obligation belge d'e-facturation dans les marchés publics a été cadrée par l'`AR` du `9 mars 2022` ;
- [[entities/mercurius|Mercurius]] peut servir de solution transitoire ou de portail de suivi si l'entreprise n'est pas encore complètement équipée ;
- l'objectif reste néanmoins l'usage d'un outil capable d'émettre des factures électroniques structurées de manière native.

Pour le `SPW`, le tome A rappelle aussi les modalités de rappel : envoi vers le centre de scanning du `SPW Finances`, avec usage privilégié du canal digital et reprise minimale des références de facture, date, montant et référence de commande.

### Lien avec les paiements

Le tome A rappelle aussi que :

- les travaux sont payés par acomptes mensuels ;
- les états d'avancement doivent reprendre les postes dans l'ordre du métré récapitulatif ;
- les travaux modificatifs dûment approuvés doivent y être mentionnés de la même manière ;
- les pénalités, amendes et retenues sont déduites des acomptes puis, si nécessaire, du [[concepts/cautionnement|Cautionnement]].

La facturation électronique s'insère donc dans un dispositif plus large de paiement structuré, et pas dans un simple échange de facture libre.

### Mentions minimales obligatoires

Le tome A liste un bloc documentaire minimum qui conditionne la régularité de la facture. Pour le `SPW`, il faut notamment retrouver :

- la référence de facture et la période de facturation ;
- les coordonnées complètes de l'adjudicataire ;
- les références du marché, du `VISA`, de l'engagement juridique et du bon de commande si applicable ;
- un état détaillé des prestations par poste ;
- le régime de `TVA` applicable, y compris la mention `autoliquidation` lorsque le régime de travaux immobiliers l'impose ;
- l'identification comptable et l'adresse de facturation du `SPW`.

L'absence d'une de ces mentions rend la facture irrégulière et justifie son renvoi.

## Implications de livraison

### Hors SPW

Le tome A prévoit aussi un schéma générique pour un adjudicateur autre que le `SPW` :

- facturation électronique via `PEPPOL` ou [[entities/mercurius|Mercurius]] ;
- rappel envoyé à la personne ou adresse désignée par le marché ;
- mêmes exigences de base sur l'identification de la facture, du vendeur, de l'acheteur, du contrat, du compte bancaire et du détail des prestations.

La [[entities/regie-des-batiments|Régie des Bâtiments]] donne un exemple fédéral concret :

- factures électroniques uniquement depuis le `1er mars 2024` ;
- envoi via `Peppol` ou [[entities/mercurius|Mercurius]] ;
- choix du client `Regie der Gebouwen-Régie des Bâtiments (0208312646)` dans [[entities/mercurius|Mercurius]] ;
- refus des factures papier ou envoyées par email.

## Bonnes pratiques techniques

Au niveau opérationnel, il est prudent de :

- vérifier avant attribution si l'outil comptable émet bien des factures structurées ;
- tester `Peppol` ou [[entities/mercurius|Mercurius]] avant la première facture ;
- préparer les références de marché et champs comptables exigés par le pouvoir adjudicateur ;
- aligner les états d'avancement, la facturation et les pièces justificatives pour éviter les rejets.

## Importance pour l'entreprise

Une entreprise qui gagne le marché doit vérifier très tôt si son flux de facturation est compatible `PEPPOL` et si ses modèles de facture couvrent toutes les mentions contractuelles. Sinon, le risque n'est pas théorique : il se traduit en retards de traitement, incompréhensions administratives et tension de trésorerie.

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
