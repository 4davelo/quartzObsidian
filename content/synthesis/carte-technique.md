---
aliases: ["Carte Technique", "Carte des connaissances — Technique HVAC"]
tags: [hub, navigation, synthese]
sources: []
created: 2026-04-23
updated: 2026-04-23
contextes: [technique]
autorite: [reference]
juridictions: [generique]
---

# Carte des connaissances — Technique HVAC

Point d'entrée pour les connaissances techniques pures d'installation HVAC : physique, dimensionnement, méthodes, équipements, commissioning. Inclut les ouvrages, guides fabricants, et bonnes pratiques de terrain.

Cette page est générée dynamiquement par Obsidian Dataview. Ouvrir dans Obsidian pour voir les résultats.

## Ouvrages et bonnes pratiques

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "technique")
  AND (contains(autorite, "pratique") OR contains(autorite, "reference"))
SORT default(aliases[0], file.name) ASC
```

## Normes techniques applicables

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "technique")
  AND contains(autorite, "normatif")
SORT default(aliases[0], file.name) ASC
```

## Chevauchements avec soumissions

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "technique")
  AND contains(contextes, "appel-doffres")
SORT default(aliases[0], file.name) ASC
```

## Chevauchements avec exécution de projet

```dataview
TABLE WITHOUT ID link(file.path, default(aliases[0], file.name)) AS Page
FROM "wiki"
WHERE !startswith(file.path, "wiki/documents/")
  AND !contains(tags, "hub")
  AND contains(contextes, "technique")
  AND contains(contextes, "execution-projet")
SORT default(aliases[0], file.name) ASC
```

## Voir aussi

- [[synthesis/carte-soumissions|Carte des connaissances — Soumissions]] — usage des connaissances techniques dans les offres
- [[synthesis/carte-execution-projet|Carte des connaissances — Exécution de projet]] — application chantier, réception et mise en service
