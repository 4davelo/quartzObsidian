---
aliases: ["Fermetures et Finitions Extérieures"]
tags: [concept, facade, enveloppe, menuiserie, finitions, interfaces]
sources: [T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf, T0 Entreprise _ Chantier CCTB 01.13_20260317.pdf]
created: 2026-04-22
updated: 2026-04-29
contextes: [technique, appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
disciplines: [enveloppe]
---
# Fermetures et Finitions Extérieures

## Définition

Dans le tome T4 du [[entities/cctb|CCTB]], les fermetures et finitions extérieures couvrent l'ensemble des ouvrages qui ferment, protègent, habillent et finissent l'enveloppe verticale extérieure du bâtiment. Le périmètre englobe les menuiseries extérieures, portes, façades rideaux, protections solaires, vitrages, bardages, revêtements de façade, pare-pluie, étanchéité à l'air, isolation extérieure, escaliers extérieurs, garde-corps, sols extérieurs et ferronneries.

## Ce que couvre le tome T4

Le tome est structuré en sept blocs qui doivent être lus ensemble :

- `41` menuiseries extérieures, portes, façades, protections solaires, ouvertures de ventilation et accessoires ;
- `42` vitrages extérieurs et éléments de remplissage ;
- `43` revêtements de façade, joints, raccords et finitions ;
- `44` étanchéisation et isolation des parois extérieures ;
- `45` escaliers extérieurs, rampes et rails d'entretien ;
- `46` revêtements de sols extérieurs et finitions diverses ;
- `47` ferronnerie d'art.

Pour un lot HVAC, T4 n'est pas un tome de production, de distribution ni de régulation. C'est le tome qui décrit comment les techniques traversent, utilisent, chargent ou modifient la façade et l'enveloppe verticale sans en dégrader les performances.

## Interfaces HVAC directes

### `41` Menuiseries extérieures et façades

Le chapitre `41` intéresse le HVAC dès qu'une installation utilise une baie, une menuiserie ou une façade comme support d'interface :

- les fenêtres, portes et façades doivent atteindre des performances de perméabilité à l'air, d'étanchéité à l'eau, de résistance au vent, de performance thermique et d'acoustique ;
- les profils sont explicitement conçus pour recevoir vitrages, panneaux, quincailleries, grilles de ventilation, protections solaires et, le cas échéant, ventilateurs éventuels ;
- la jonction au gros-oeuvre doit assurer la continuité de l'isolation, de l'étanchéité à l'air, de l'étanchéité à l'eau et de l'acoustique ;
- les façades rideaux et double peau ajoutent des contraintes de contrôle solaire, de condensation, de feu, de mouvements du gros-oeuvre et d'ancrage.

En pratique, cela vise les [[concepts/menuiseries-exterieures-et-facades|Menuiseries Extérieures et Façades]], les prises d'air en façade, les rejets, les traversées de façade rideau, les terminaux intégrés dans baies, les locaux techniques ventilés naturellement et les enveloppes de halls techniques ou d'atriums.

### `41.52` Protections solaires

Le chapitre `41.52` est une interface directe entre façade et stratégie thermique :

- les protections solaires font l'objet d'une étude fabricant sur le positionnement, l'orientation et le pas des lames en fonction de l'exposition ;
- les ancrages doivent éviter la création de ponts thermiques ;
- les performances de facteur solaire `gtot`, de transmission lumineuse, de résistance au vent, d'endurance et de manœuvre sont encadrées ;
- la continuité d'étanchéité à l'air est explicitement demandée au pourtour des caissons de stores.

Pour le HVAC, cela touche le calcul de surchauffe, les charges de refroidissement, le confort d'été et la cohérence entre façade, régulation et consignes de confort.

### `41.75` Ouvertures de ventilation

Le chapitre `41.75` est le noyau de l'interface façade / ventilation naturelle :

- il rappelle la logique des systèmes `A`, `B`, `C` et `D` de `NBN D 50-001` ;
- il traite les ouvertures d'amenée d'air réglables dans le mur, la baie hors châssis, la quincaillerie, le vitrage ou le profil de châssis ;
- il dimensionne ces amenées sur base du débit nominal sous `2 Pa` ;
- il exige des performances acoustiques adaptées aux zones bruyantes.

Cette matière est détaillée dans [[concepts/ouvertures-de-ventilation-en-facade|Ouvertures de Ventilation en Façade]].

### `42` Vitrages et remplissages

Le chapitre `42` compte pour le HVAC parce qu'il porte le contrôle solaire réel de la façade :

- les valeurs de vitrage, panneaux et remplissages conditionnent `Ug`, `Up`, transmission lumineuse et facteur solaire ;
- les vitrages doubles, triples, sous vide, à traitement anti-radiations ou avec stores intégrés modifient directement la charge thermique de la baie ;
- les remplissages opaques ou sandwich modifient aussi les valeurs globales des châssis, portes et façades.

Cette matière est détaillée dans [[concepts/vitrages-exterieurs-et-elements-de-remplissage|Vitrages Extérieurs et Éléments de Remplissage]].

### `43` Revêtements de façade et traversées

Le chapitre `43` devient critique dès qu'un équipement technique est fixé sur, ou traverse, l'enveloppe extérieure :

- les bardages et systèmes ETICS durs prévoient des réservations, des découpes, des chevêtres, des finitions de bords et des renforts pour charges techniques ;
- les systèmes étanches pour traversées de murs rétablissent la continuité de l'air, du thermique et parfois du feu ;
- les façades ventilées imposent une articulation avec pare-pluie, lame d'air, anti-rongeurs et détails de baies.

Cette matière est détaillée dans [[concepts/revetements-de-facade|Revêtements de Façade]].

### `44` Pare-pluie, étanchéité à l'air et isolation extérieure

Le chapitre `44` encadre les couches de protection qui se trouvent derrière ou autour des éléments techniques :

- les pare-pluie doivent être continus, raccordés et compatibles avec les traversées techniques ;
- l'étanchéisation aux matières gazeuses prolonge la logique d'étanchéité à l'air de l'enveloppe ;
- l'isolation extérieure est décrite à la fois pour la thermique et l'acoustique, avec articulation aux autres tomes.

Cette matière est détaillée dans [[concepts/etancheisation-et-isolation-des-parois-exterieures|Étanchéisation et Isolation des Parois Extérieures]].

## Obligations transversales pour le lot HVAC

Au-delà des articles particuliers, T4 impose une discipline d'enveloppe :

- prévoir les terminaux, grilles, caissons, fixations et traversées dès les détails d'exécution ;
- maintenir les continuités air + eau + thermique + acoustique et, selon les cas, feu ;
- ne pas considérer un bardage, un châssis ou un ETICS comme un simple support "perçable" ;
- vérifier les ponts thermiques au niveau des fixations, caissons et consoles ;
- coordonner les réservations et renforts avec gros-oeuvre, façade, enduits, bardages et électricité ;
- documenter les positions exactes des interfaces façade dans les plans, métrés, notes de calcul et as-built.

## Résumé du reste du tome pour situer le lot

Le reste de T4 ancre l'interface HVAC dans un lot plus large que la seule ventilation ou climatisation :

- `41` décrit aussi tous les types de fermetures extérieures courantes et leurs performances d'usage ;
- `42` couvre les variantes complètes de vitrages et remplissages, y compris en rénovation ;
- `43` décrit la variété réelle des bardages, parements, enduits, joints, rives et couvre-murs déjà présents en façade ;
- `45` à `47` rappellent que le lot extérieur comprend aussi des ouvrages d'accès, de sécurité, de finition et de paysage.

Autrement dit, le lot façade n'est pas un arrière-plan neutre des techniques spéciales. C'est un lot complet d'enveloppe, de sécurité, de performance énergétique, d'acoustique, de feu et de durabilité. Le HVAC ne peut s'y raccorder correctement qu'en lisant ce contexte complet.

## Importance pour un marché public

Dans une réponse publique, T4 sert à démontrer que les techniques restent compatibles avec la façade réellement prescrite. Si une amenée d'air, un store, un terminal ou une fixation technique dégrade la façade au point de vue air, eau, acoustique, thermique ou feu, l'offre HVAC reste incomplète même si l'équipement est correctement dimensionné.

## Pages liées

- [[concepts/menuiseries-exterieures-et-facades|Menuiseries Extérieures et Façades]]
- [[concepts/ouvertures-de-ventilation-en-facade|Ouvertures de Ventilation en Façade]]
- [[concepts/protections-solaires-exterieures|Protections Solaires Extérieures]]
- [[concepts/vitrages-exterieurs-et-elements-de-remplissage|Vitrages Extérieurs et Éléments de Remplissage]]
- [[concepts/revetements-de-facade|Revêtements de Façade]]
- [[concepts/etancheisation-et-isolation-des-parois-exterieures|Étanchéisation et Isolation des Parois Extérieures]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
