# Mastering IA - État du projet

## But de l'application
Application web mobile qui :
- analyse un son
- agit comme un ingénieur du son via IA
- embellit le rendu audio
- masterise le morceau
- livre un fichier final prêt à télécharger

## Objectif produit
Créer une application simple, rapide et premium depuis mobile, pensée d’abord pour le mode :
- voix + instrumental séparés

Ce mode est prioritaire car il permet un traitement audio plus propre, plus précis et plus professionnel.

## Utilisateur cible
- artistes
- rappeurs
- créateurs de contenu
- utilisateurs mobile qui veulent un son plus propre sans logiciel compliqué

## Fonctionnement attendu
1. importer les fichiers
2. analyser le son
3. générer un résumé IA
4. construire un plan de traitement comme un ingénieur du son
5. traiter la voix et l’instrumental
6. recombiner
7. masteriser
8. télécharger le fichier final

## Stack actuelle
- Frontend : Vercel
- Backend : Render
- IA : OpenAI
- Analyse audio : Python
- Traitement audio : FFmpeg
- Stockage / base éventuelle : Supabase

## Fichiers importants
- `frontend/index.html`
- `backend/server.js`
- `backend/analyze.py`

## Ce qui fonctionne déjà
- interface frontend en ligne
- choix du mode fichier complet ou voix + instru
- import des fichiers audio
- aperçu audio des fichiers importés
- analyse du fichier complet
- analyse séparée voix + instrumental
- résumé IA généré
- plan IA généré comme un ingénieur du son
- traitement du mode voix + instru
- téléchargement du fichier final
- statut et progression visibles
- copie du résumé et du détail

## Version actuelle
- V6 moteur audio validée
- traitement réel validé
- fichier final téléchargé avec succès
- prochaine grosse étape : interface premium + monétisation visuelle

## Résultat validé
Le workflow validé est :
- analyser
- générer le plan IA
- traiter
- télécharger le produit final

## Bugs importants déjà corrigés
- bug Vercel 404 causé par mauvaise racine / mauvais projet
- bug `makeup=0.8` FFmpeg corrigé
- problème de traitement stems corrigé
- téléchargement final validé

## Problèmes à surveiller
- bien redéployer sur Render quand `backend/server.js` change
- bien redéployer sur Vercel quand `frontend/index.html` change
- toujours vérifier que le bouton `Traiter` lance bien le backend actuel

## Règle de travail importante
Cheikh est sur téléphone Android uniquement.
Toujours donner :
- des fichiers complets
- prêts à copier-coller
- sans demander de petites modifications compliquées ligne par ligne

## État du frontend
Interface actuelle déjà fonctionnelle avec :
- hero principal
- mode clair / sombre
- import audio
- résumé premium
- détail complet
- statut
- progression

## État du backend
Le backend :
- analyse
- génère un plan IA
- traite les stems
- exporte le fichier final

## Vision produit
Le produit final doit être :
- simple
- premium
- rapide
- mobile first
- monétisable par crédits

## Idée de monétisation
Monétisation envisagée :
- packs de crédits
- paiement à l’usage
- pas forcément abonnement au début

Exemples de packs affichables :
- découverte
- créateur
- studio

## URLs à compléter
- Frontend Vercel : À compléter
- Backend Render : À compléter

## Dernière validation connue
Validation réussie :
- résumé IA généré
- traitement appliqué
- produit final généré
- fichier final téléchargé

## Prochain objectif
Passer en V7 interface premium :
- réduire certains blocs
- améliorer la lisibilité
- ajouter une vraie zone résultat final
- ajouter lecteur audio du rendu final
- ajouter bouton téléchargement visible
- ajouter section monétisation visuelle

## Étape après V7
Passer en V8 monétisation réelle :
- Stripe ou Lemon Squeezy
- packs de crédits
- logique de consommation des crédits

## Consigne de reprise si conversation perdue
Si la conversation est perdue, repartir avec :
1. ce fichier `PROJECT_STATE.md`
2. le fichier `NEXT_TASK.md`
3. le fichier à modifier en entier
