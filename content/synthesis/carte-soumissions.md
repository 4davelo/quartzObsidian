---
aliases: ["Carte Soumissions", "Carte des connaissances — Soumissions"]
tags: [hub, navigation, synthese]
sources: []
created: 2026-04-23
updated: 2026-04-23
contextes: [appel-doffres]
autorite: [reference]
juridictions: [generique]
---

# Carte des connaissances — Soumissions

Point d'entrée pour la préparation et la remise d'offres sur marchés publics HVAC. Les pages listées couvrent les exigences contractuelles (CCTB), le cadre réglementaire, les normes applicables, et les bonnes pratiques de rédaction d'offre.

Cette page est générée dynamiquement par Obsidian Dataview. Ouvrir dans Obsidian pour voir les résultats.

## Pages contractuelles et réglementaires

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "appel-doffres")
  AND (contains(autorite, "contractuel") OR contains(autorite, "reglementaire"))
SORT default(aliases[0], file.name) ASC
```

## Normes applicables

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "appel-doffres")
  AND contains(autorite, "normatif")
SORT default(aliases[0], file.name) ASC
```

## Références et bonnes pratiques

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "appel-doffres")
  AND (contains(autorite, "reference") OR contains(autorite, "pratique"))
SORT default(aliases[0], file.name) ASC
```

## Chevauchements avec exécution de projet

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "appel-doffres")
  AND contains(contextes, "execution-projet")
SORT default(aliases[0], file.name) ASC
```

## Voir aussi

- [[synthesis/carte-execution-projet|Carte des connaissances — Exécution de projet]] — continuité entre offre et exécution
- [[synthesis/carte-technique|Carte des connaissances — Technique HVAC]] — connaissances techniques mobilisées en soumission
