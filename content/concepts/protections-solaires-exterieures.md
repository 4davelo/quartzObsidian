---
aliases: ["Protections Solaires Extérieures"]
tags: [concept, facade, solaire, confort-ete, enveloppe, hvac]
sources: [T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf, T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf]
created: 2026-04-22
updated: 2026-04-29
contextes: [technique, appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
disciplines: [enveloppe, cvc]
---
# Protections Solaires Extérieures

## Définition

Dans le tome T4 du [[entities/cctb|CCTB]], les protections solaires extérieures regroupent les systèmes fixes ou mobiles placés en façade pour limiter les apports solaires, moduler la lumière et protéger les baies. Elles comprennent notamment des systèmes à lamelles orientables ou fixes, des panneaux perforés et des stores à toile.

## Pourquoi c'est un sujet HVAC

Même si T4 traite ces ouvrages comme un lot façade, leur effet est directement HVAC :

- réduction des surchauffes ;
- diminution des charges de refroidissement ;
- modulation du confort lumineux et du facteur solaire ;
- cohérence entre stratégie de façade, ouvrants, vitrage et régulation.

## Ce que T4 impose

Le tome ne traite pas la protection solaire comme un simple accessoire :

- le fabricant doit étudier le dimensionnement des supports et ancrages ;
- les fixations doivent éviter la création de ponts thermiques ;
- le positionnement, l'inclinaison et le pas des lames doivent être choisis selon l'orientation des baies ;
- les notes de calcul et plans de détail sont soumis à approbation.

## Performances importantes

T4 encadre plusieurs familles de performance utiles au HVAC :

- résistance au vent selon `NBN EN 13561` ;
- endurance mécanique en cycles ;
- efforts de manœuvre manuels ;
- compatibilité électromagnétique et sécurité électrique des motorisations ;
- résistance thermique additionnelle `Delta-R` lorsque la fermeture participe à l'isolation ;
- facteur de transmission de l'énergie solaire `gtot` et transmission lumineuse.

La classification `gtot` reprise par le tome correspond à une lecture énergétique concrète :

- classe `0` si `gtot >= 0,50` ;
- classe `1` si `0,35 <= gtot < 0,50` ;
- classe `2` si `0,15 <= gtot < 0,35` ;
- classe `3` si `0,10 <= gtot < 0,15` ;
- classe `4` si `gtot < 0,10`.

Pour le HVAC, cette gradation permet de relier la façade au calcul de confort d'été.

## Variantes décrites dans T4

Le tome distingue notamment :

- protections fixes à lamelles orientables ;
- protections fixes à lamelles fixes ;
- protections fixes par panneaux ;
- protections mobiles à lamelles orientables ;
- protections mobiles à lamelles fixes ;
- protections mobiles par panneaux ;
- protections mobiles par toile.

Les systèmes mobiles peuvent être manuels ou motorisés. Certaines commandes peuvent être couplées à des détecteurs de luminosité et de vitesse du vent.

## Points d'interface avec l'enveloppe

T4 impose des précautions d'enveloppe souvent négligées en pratique :

- étanchéité à l'air sur tout le pourtour du caisson à stores ;
- continuité avec le gros-oeuvre et le châssis ;
- fixations et supports en matériaux inoxydables ;
- coordination avec les menuiseries et les détails de linteau ;
- obligation de décrire clairement le mode de pose, l'usage et l'entretien.

Dans les protections à toile, la motorisation est asservie par défaut à un capteur de vent qui replie la toile à `50 km/h`, ce qui montre bien que T4 relie la performance solaire à la tenue en service.

## Importance pour un marché public

Dans un marché public, la protection solaire extérieure ne peut pas être laissée comme un simple poste "architectural". Elle conditionne une partie du comportement thermique d'été, la qualité d'usage des locaux, les détails d'étanchéité et la coordination T4/T7. Pour un lot HVAC, elle doit au minimum être lue comme une donnée d'entrée sérieuse de confort et de charge.

## Pages liées

- [[concepts/fermetures-et-finitions-exterieures|Fermetures et Finitions Extérieures]]
- [[concepts/menuiseries-exterieures-et-facades|Menuiseries Extérieures et Façades]]
- [[concepts/vitrages-exterieurs-et-elements-de-remplissage|Vitrages Extérieurs et Éléments de Remplissage]]
- [[concepts/qualite-de-lair-interieur|Qualité de l'Air Intérieur]]
- [[concepts/climatisation-et-froid|Climatisation et Froid]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
