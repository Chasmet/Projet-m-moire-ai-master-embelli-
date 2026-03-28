# Mastering IA - État du projet

## But de l'application
Application web mobile qui :
- analyse un son
- agit comme un ingénieur du son via IA
- embellit le rendu audio
- applique un final master
- livre un fichier final prêt à télécharger

## Positionnement produit
Mastering IA embellit d’abord le son, puis applique un final master pour livrer un rendu final plus propre, plus puissant et prêt à l’écoute.

## Règle commerciale
- 1 génération = embellissement + final master + export du fichier final
- le mode voix + instrumental séparés est prioritaire pour la meilleure qualité

## Utilisateur cible
- artistes
- rappeurs
- créateurs de contenu
- utilisateurs mobile qui veulent un son plus propre sans logiciel compliqué

## Stack actuelle
- Frontend : Vercel
- Backend : Render
- IA : OpenAI
- Analyse audio : Python
- Traitement audio : FFmpeg
- Base prévue pour comptes / admin : Supabase

## Fichiers importants
- `frontend/index.html`
- `backend/server.js`
- `backend/analyze.py`

## Ce qui fonctionne déjà
- interface frontend en ligne
- mode fichier complet
- mode voix + instru
- import des fichiers audio
- aperçu audio des fichiers importés
- analyse du fichier complet
- analyse séparée voix + instrumental
- résumé IA généré
- plan IA généré comme un ingénieur du son
- traitement du mode voix + instru
- téléchargement du fichier final
- résultat final visible dans l’interface
- packs visuels affichés dans l’interface
- wording “embellissement + final master” intégré

## Version actuelle
- V8 packs + générations + final master
- l’application publique fonctionne
- pas encore de bouton Admin
- pas encore de login client
- pas encore de login admin
- pas encore de base de données utilisateurs branchée
- pas encore de comptabilité admin dans l’app

## Monétisation validée
Nom commercial :
- générations

Packs validés :
- Découverte : 3 générations - 1,49 €
- Créateur : 10 générations - 3,99 €
- Studio : 25 générations - 7,99 €

## Paiement envisagé
- Revolut
- ajout manuel des générations au début
- automatisation plus tard

## Vision admin
Le prochain vrai objectif est de faire une V10 directe avec :
- bouton Admin
- connexion admin par email + mot de passe
- espace admin privé
- suivi ventes
- suivi dépenses
- rapport trimestriel clair pour URSSAF
- possibilité pour Cheikh d’utiliser l’app en mode admin

## Vision client
À terme :
- connexion client
- achat de générations
- génération décomptée au moment du traitement final
- analyse consultable
- traitement consommant 1 génération

## Entreprise
- petite entreprise créée / activité digitale lancée
- objectif : encaisser légalement avec l’application

## Bugs importants déjà corrigés
- bug Vercel 404 causé par mauvaise racine / mauvais projet
- bug FFmpeg `makeup=0.8` corrigé
- traitement stems validé
- téléchargement final validé

## Règle de travail importante
Cheikh est sur téléphone Android uniquement.
Toujours fournir :
- des fichiers complets
- prêts à coller
- sans micro-modifications compliquées
- avec le nom du fichier affiché seul quand demandé

## URLs à compléter
- Frontend Vercel : À compléter
- Backend Render : À compléter

## Prochain objectif
Passer directement à la V10 admin :
- bouton Admin
- login email + mot de passe
- espace admin privé
- base pour comptabilité
- rapport trimestriel clair

## Reprise si conversation perdue
Si la conversation est perdue, repartir avec :
1. ce fichier `PROJECT_STATE.md`
2. le fichier `NEXT_TASK.md`
3. le ou les fichiers à modifier
