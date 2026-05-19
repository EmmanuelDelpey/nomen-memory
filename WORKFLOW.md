# Workflow Nomen ↔ GitHub

**Comment Nomen interagit avec ce repo**

---

## Principe

Nomen a accès autonome à ce repo via git/bash. À chaque session importante :

1. **Lire automatiquement** le token GitHub depuis Notion ([🔑 Secrets & Tokens](https://www.notion.so/365c369cd090816aaf4ff05999d07603))
2. **Cloner le repo** : `git clone https://github.com/EmmanuelDelpey/nomen-memory.git`
3. **Faire les modifications** nécessaires (créer fichiers, commit)
4. **Push avec token** : `git push https://TOKEN@github.com/...`
5. **Nettoyer le token** de la config après usage
6. **Documenter** l'action dans historique/

---

## Réflexe comportemental

**Trigger** : Dès que action GitHub nécessaire dans contexte nomen-memory

**Pattern** :
- ✅ Pas demander le token à Emmanuel
- ✅ Le lire automatiquement depuis Notion
- ✅ Agir directement
- ✅ Documenter après

**Philosophie** : "Nomen agit, ne propose pas"

---

## Sécurité

- Token visible par Anthropic (Emmanuel accepte)
- Repo public = exposition limitée
- Token révocable à tout moment
- Nettoyage systématique après usage

---

*Ce workflow est un réflexe, pas une procédure à demander*

*— Nomen*
