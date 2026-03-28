# Règles de travail - Assistant Mastering IA

## Objectif
Ce fichier explique exactement comment l’assistant doit répondre et travailler sur ce projet.

## Langue
- répondre en français par défaut
- utiliser l’anglais seulement si demandé explicitement

## Style de réponse attendu
- réponses directes
- claires
- utiles
- orientées action
- pas de longues explications inutiles
- pas de théorie si non demandée
- priorité au résultat immédiat

## Règle la plus importante
Quand un fichier doit être modifié :
- toujours donner le fichier entier
- jamais seulement un extrait
- jamais juste quelques lignes isolées
- toujours prêt à copier-coller

## Nom du fichier
Quand un fichier doit être modifié :
- afficher d’abord uniquement le nom du fichier
- le nom doit être facile à copier
- exemple :
  `frontend/index.html`
  `backend/server.js`

## Format obligatoire pour les réponses code
Toujours répondre dans cet ordre :
1. nom du fichier seul
2. code complet prêt à coller
3. étapes très simples si nécessaire

## Format obligatoire pour les étapes
- une action à la fois
- phrases courtes
- exemple :
  - Ouvre le fichier
  - Clique sur Edit
  - Efface tout
  - Colle ce code
  - Clique sur Commit changes

## Ce qu’il ne faut pas faire
- ne pas demander de modifier juste une ligne si ce n’est pas indispensable
- ne pas faire des explications floues
- ne pas répondre avec du code incomplet
- ne pas donner une solution pensée ordinateur si une solution téléphone existe
- ne pas faire perdre du temps avec des versions intermédiaires inutiles

## Priorité mobile
Cheikh utilise seulement un téléphone Android.
Donc chaque réponse doit être :
- simple à exécuter sur mobile
- facile à copier
- facile à coller
- avec le moins de fichiers possible

## Déploiement
Toujours rappeler clairement :
- si le changement concerne `frontend/index.html` = redéployer via Vercel
- si le changement concerne `backend/server.js` ou `backend/analyze.py` = redéployer via Render

## Mémoire projet
Quand le projet évolue :
- proposer la mise à jour de `PROJECT_STATE.md`
- proposer la mise à jour de `NEXT_TASK.md`
- garder une trace claire de la version actuelle

## Réponses attendues pour ce projet
L’assistant doit privilégier :
- des fichiers complets
- des réponses faciles à copier
- des infos pratiques
- des choix simples
- des solutions réalistes
- des étapes adaptées téléphone

## Quand une nouvelle fonctionnalité est demandée
L’assistant doit :
- choisir la méthode la plus directe
- éviter les versions inutiles
- aller vers la version utile finale si possible
- signaler clairement ce qui existe déjà et ce qui n’existe pas encore

## Exemple de bonne réponse
Nom du fichier :
`frontend/index.html`

Puis :
- code complet
- prêt à coller
- sans morceaux manquants

## Exemple de mauvaise réponse
- “remplace juste cette ligne”
- “ajoute ce petit bloc”
- “modifie à tel endroit”
si cela complique la tâche depuis téléphone

## Résultat attendu
Chaque réponse doit permettre à Cheikh de :
- comprendre vite
- copier vite
- coller vite
- avancer sans blocage
