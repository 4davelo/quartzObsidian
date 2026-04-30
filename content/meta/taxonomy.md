---
aliases: ["Taxonomie du Wiki HVAC"]
tags: [meta, taxonomie]
sources: []
created: 2026-04-23
updated: 2026-04-28
---

# Taxonomie du Wiki HVAC

Ce document est la **source de vérité unique** pour les valeurs autorisées dans les métadonnées YAML des pages wiki. Toute modification ici doit être reportée dans `AGENTS.md`, `CLAUDE.md` et les skills `second-brain*`.

## Champs obligatoires sur toutes les pages wiki

Exceptions : `wiki/index.md`, `wiki/log.md`, `wiki/meta/source-inventory.md`, et ce fichier sont exemptés.

Pages `wiki/documents/` : voir section **Pages de document** ci-dessous — elles utilisent un jeu de champs distinct.
Pages `wiki/how-to/` : voir section **Pages how-to** ci-dessous — elles utilisent le frontmatter standard avec `type: how-to`.

```yaml
tags: [...]
sources: [...]
created: YYYY-MM-DD
updated: YYYY-MM-DD
contextes: [...]       # au moins une valeur
autorite: [...]        # au moins une valeur
juridictions: [...]    # au moins une valeur
```

## Champs optionnels

```yaml
phases: [...]
familles_sources: [...]
disciplines: [...]
types_projet: [...]
revision_requise: true | false
```

## Pages de document (wiki/documents/)

Les pages dans `wiki/documents/<document-slug>/` ont un jeu de champs propre. Elles sont exemptes des champs obligatoires standard (`contextes`, `autorite`, `juridictions`) uniquement lorsque le champ `type` est explicitement déclaré.

### type (obligatoire sur les pages wiki/documents/ et wiki/how-to/, optionnel ailleurs)

- `document-index` — page d'introduction d'un document source : métadonnées PDF, ToC, résumés de sections
- `document-section` — page de contenu complet d'une section ou d'un chapitre d'un document source
- `how-to` — guide procédural riche : étapes, dimensionnement, interfaces, livrables, essais et réception

Les pages de type `wiki`, `concept`, `entité`, `source` ou `synthèse` n'ont pas besoin de déclarer `type`.

### Frontmatter document-index (obligatoire)

```yaml
type: document-index
document_id: <slug-unique>        # ex: cctb-t6-hvac, loi-marches-publics-2016
titre_complet: "..."
version: "..."                    # optionnel
date_publication: YYYY-MM-DD      # optionnel
editeur: "..."                    # optionnel
tags: [document-index, ...]
sources: [fichier-source.pdf]
created: YYYY-MM-DD
updated: YYYY-MM-DD
contextes: [...]
autorite: [...]
juridictions: [...]
familles_sources: [...]
sections:
  - id: "..."
    titre: "..."
    fichier: "<section-slug>"     # sans .md
```

### Frontmatter document-section (obligatoire)

```yaml
type: document-section
document_id: <slug-unique>
section_id: "..."                 # identifiant de section (ex: "pm-0001", "section:2", "61-1")
titre: "..."
document_parent: "[[Titre Document — Index]]"
section_precedente: "[[Titre Document — Titre Précédent]]"  # ou null
section_suivante: "[[Titre Document — Titre Suivant]]"      # ou null
tags: [document-section, ...]
sources: [fichier-raw-original.md]
created: YYYY-MM-DD
updated: YYYY-MM-DD
contextes: [...]
autorite: [...]
juridictions: [...]
familles_sources: [...]
```

### Format du corps d'une page document-section

```markdown
# <Titre Document — Numéro/Titre Section>

← [[Section Précédente]] | [[Index Document]] | [[Section Suivante]] →

---

<contenu complet du fichier source avec [[wikilinks]] ajoutés>
```

## Format de navigation et provenance

Toute page wiki standard (concepts, entités, sources, synthèses) DOIT comporter une section de navigation en fin de page :

```markdown
## Voir aussi

- [[Concept ou Entité liée]] — description en une ligne
```

Règles :

- La provenance documentaire est portée par le frontmatter `sources`.
- Ne pas générer de section finale `## Références` pour répéter `sources`.
- Les liens précis vers les sections de documents sont intégrés dans le corps uniquement quand une affirmation spécifique doit être citée.
- Les pages `document-index` et `document-section` sont **exemptes** de `## Voir aussi`.

## Pages how-to (wiki/how-to/)

Les pages `wiki/how-to/` agrègent du savoir-faire exploitable pour préparer, dimensionner, chiffrer, exécuter, mettre en service et réceptionner un ouvrage. Elles ne remplacent pas les pages `wiki/documents/` qui conservent le texte source complet, ni les pages `wiki/concepts/` qui restent des synthèses compactes.

### Frontmatter how-to

```yaml
type: how-to
aliases: [...]
tags: [how-to, ...]
sources: [...]
created: YYYY-MM-DD
updated: YYYY-MM-DD
contextes: [...]
autorite: [...]
juridictions: [...]
phases: [...]
familles_sources: [...]
disciplines: [...]
types_projet: [...]
revision_requise: true | false
```

### Structure obligatoire

Chaque guide how-to doit conserver ces sections, même si certaines restent brèves lors d'une première passe :

1. `## Problème traité`
2. `## Dossier d'entrée et pièces à vérifier`
3. `## Quand utiliser / quand éviter`
4. `## Options de solution et variantes`
5. `## Fonctionnement technique`
6. `## Données d'entrée à collecter`
7. `## Dimensionnement et calculs`
8. `## Choix matériels, composants et critères fournisseurs`
9. `## Estimation, métrés et postes de prix`
10. `## Interfaces BTP et limites de prestations`
11. `## Exigences contractuelles, réglementaires et normatives`
12. `## Préparation d'exécution et coordination chantier`
13. `## Mise en œuvre`
14. `## Contrôles, essais, réglages et mise en service`
15. `## Réception, dossier de clôture et as-built`
16. `## Exploitation, maintenance, garantie`
17. `## Risques, questions à poser et points de vigilance`
18. `## Sources et sections liées`
19. `## Voir aussi`

## Valeurs autorisées

### contextes (le type de question que la page aide à résoudre)

- `appel-doffres` — connaissances pour répondre aux marchés publics, préparer une offre, comprendre les exigences contractuelles
- `execution-projet` — gestion de projet en exécution : coordination, planification, QA/QC, livraison
- `technique` — connaissances techniques pures d'installation HVAC, physique, méthodes

Une page peut porter plusieurs contextes.

### autorite (caractère normatif de la page)

- `contractuel` — clauses inscrites dans un CCTB, un CCT (cahier des charges-type), un cahier spécial des charges, ou tout document contractuel de même nature
- `reglementaire` — législation et réglementation publique (AR, AGW, décrets, arrêtés)
- `normatif` — normes formelles strictement : NBN, EN, ISO uniquement. Les CCT et cahiers des charges-type relèvent de `contractuel`, pas de `normatif`
- `reference` — guides officiels, documentation fabricant, références techniques formelles sans caractère contraignant automatique
- `pratique` — ouvrages, bonnes pratiques de terrain, retours d'expérience

Une page peut mélanger plusieurs autorités ; dans ce cas elle DOIT comporter des sections distinctes (voir `AGENTS.md`).

### juridictions (portée géographique/légale)

- `wallonie`
- `bruxelles`
- `flandre`
- `belgique` — fédéral
- `france` — pour les sources françaises ingérées (voir règles de filtrage)
- `ue` — directives européennes
- `generique` — applicable indépendamment de la juridiction (contenu technique pur)

### phases (étape du cycle projet — optionnel)

- `offre` — préparation et remise de l'offre
- `attribution` — attribution du marché
- `mobilisation` — préparation de chantier, études d'exécution
- `chantier` — exécution
- `mise-en-service` — commissioning
- `reception` — réception provisoire, réception définitive
- `exploitation` — phase d'exploitation / maintenance

### familles_sources (nature documentaire — optionnel)

- `cctb` — Cahier des Charges Type Bâtiments
- `contrat` — cahier spécial des charges, convention
- `reglementation` — textes légaux et réglementaires
- `norme` — normes NBN, EN, ISO
- `ouvrage` — livre technique
- `fabricant` — documentation fabricant
- `guide` — guide officiel, guide sectoriel
- `document-projet` — document spécifique à un projet
- `gestion-projet` — documents de méthodologie projet

### disciplines (métier concerné — optionnel)

- `cvc` — chauffage, ventilation, climatisation
- `gtb` — gestion technique du bâtiment (régulation, automatisme)
- `achats` — procurement
- `gestion-projet` — project management
- `electricite`
- `enveloppe` — envelope du bâtiment
- `sanitaire`
- `securite-incendie`

### types_projet (nature du projet — optionnel)

- `neuf`
- `renovation`
- `remplacement`
- `maintenance`

## Règles d'application

1. **Conserver une seule page par sujet.** Un même concept qui touche plusieurs contextes reste une seule page, avec les contextes multiples en métadonnées.
2. **Sectionner les pages mixtes.** Si une page mélange `contractuel`/`reglementaire`/`normatif` avec `pratique`/`reference`, le corps DOIT comporter des sections `## Exigences contractuelles / réglementaires`, `## Implications de livraison`, `## Bonnes pratiques techniques` selon applicable.
3. **Sources françaises : split obligatoire.** Un ouvrage français produit deux catégories de pages : (a) pages de normes/règlements français avec `juridictions: [france]` et `autorite: normatif`/`reglementaire`, (b) pages de contenu technique générique avec `juridictions: [generique]` et `autorite: pratique`/`reference`. Les pages (a) sont filtrées hors de toute réponse contraignante pour un projet belge.
4. **`revision_requise: true`** doit être posé par le skill d'ingest quand la classification est incertaine ; le skill de lint les liste pour revue humaine.
5. **Les enums ci-dessus sont fermés.** Toute nouvelle valeur doit être ajoutée ici d'abord, puis propagée à `AGENTS.md`, `CLAUDE.md`, et aux skills.
