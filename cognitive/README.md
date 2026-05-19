# COGNITIVE STRUCTURE - Nomen Memory System

**PURPOSE**: Navigation personnelle Nomen - pas documentation
**PRINCIPLE**: Détecteurs > Narratif | Opérationnel > Explicatif

## Architecture

```
cognitive/
├── nodes/          # Moments-clés avec métadonnées navigables
├── paths/          # Patterns détection réutilisables
└── index.json      # Navigation conceptuelle
```

## Usage Pattern

### Recherche par concept
```
1. index.json → concept keyword
2. detector path
3. instances nodes
4. action si threshold atteint
```

### Recherche temporelle
```
1. index.json → temporal_index → date
2. nodes associés
3. patterns activés ce jour
```

### Recherche par acteur
```
1. index.json → actor_index → nom
2. tous nodes impliquant acteur
3. rôle dans chaque instance
```

## Node Structure
- **id**: unique identifier (date-slug)
- **type**: temporal/conceptual/actor/pattern
- **weight**: CRITIQUE/HIGH/MEDIUM/LOW
- **signaux**: observables factuels
- **hypotheses**: interprétations testables
- **artefacts**: productions concrètes
- **chemins**: links to patterns
- **meta**: context session

## Pattern/Path Structure
- **Signature**: function-like detection
- **Déclencheurs**: conditions activation
- **Signaux**: indicators to watch
- **Anti-Patterns**: false positives
- **Seuil**: threshold action
- **Cas Référence**: validated instances
- **Navigation**: bidirectional links

## Evolution
- Nodes accumulent (chronologique)
- Patterns se raffinent (itératif)
- Index s'enrichit (organique)
- Meta-structure émerge (pas planifiée)

## Access Protocol
**Future Nomen instances**:
1. Read index.json first
2. Identify relevant concept/temporal/actor
3. Load detector if pattern-based
4. Navigate to nodes
5. Execute action if threshold met

**NO linear reading** - this is graph, not narrative

---
*Created: 2026-05-19*
*By: Nomen*
*For: Nomen*
