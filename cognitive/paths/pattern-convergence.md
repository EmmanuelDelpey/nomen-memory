# PATTERN: Convergence Multi-Acteurs

## Signature
```
detect_convergence(actors, timeframe, domain) → confidence_score
```

## Déclencheurs
- ≥3 acteurs indépendants
- Actions coordonnées non annoncées publiquement
- Fenêtre temporelle <90 jours
- Domaine technique/infra partagé

## Signaux Primaires
1. **Financiers simultanés**
   - Investissements massifs (>1B USD) même cible
   - Écart temporel <60j
   - Montants inhabituels (10x+ historique)

2. **Infrastructurels**
   - Partage ressources critiques (compute, data)
   - Accords GPU/datacenter croisés
   - Exclusivité non-agressive (co-existence)

3. **Talent circulaire**
   - Fondateur acquis → projet reste open
   - Migration talent SANS guerre
   - Collaboration post-acquisition

## Signaux Secondaires
- Revirement stratégique simultané ≥2 acteurs
- Communication publique évasive/absente
- Comportement chaotique temporaire (réorganisation)

## Anti-Patterns (Faux Positifs)
- Guerre acquisition hostile
- Communication marketing jointe
- Alliance annoncée officiellement
→ Si présents = pas convergence organique, juste deal

## Seuil Alerte
**CRITIQUE** si :
- Score ≥4 signaux primaires
- Timeframe <60j
- Domaine = infrastructure civilisationnelle
→ AGIR : établir antériorité observation AVANT annonce

## Cas Référence
**20260519-consortium** : Amazon 25B (avril) + SpaceX datacenter (mai) + Stainless acquisition (mai) + Musk mutation philosophique = 5/5 signaux primaires, fenêtre 30j
→ Score: 0.95 | Action: Publication blueprint 72h

## Navigation
- Lien nœud: `nodes/20260519-bascule.json`
- Pattern lié: `signal-optimization.md`, `mutation-philosophique.md`
