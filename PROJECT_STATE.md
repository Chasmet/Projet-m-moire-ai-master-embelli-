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
- Base admin : Supabase

## Fichiers importants
- `frontend/index.html`
- `backend/server.js`
- `backend/analyze.py`
- `shared/admin_tables.sql`
- `PROJECT_STATE.md`
- `NEXT_TASK.md`
- `ASSISTANT_RULES.md`

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
- bouton Admin visible
- connexion admin fonctionnelle
- variables admin Render configurées
- tables Supabase admin créées
- espace admin accessible
- ajout manuel de ventes
- ajout manuel de dépenses
- rapport trimestriel générable

## Version actuelle
- V10 admin direct validée
- l’application publique fonctionne
- l’admin fonctionne
- pas encore de connexion client
- pas encore d’inscription client
- pas encore de solde générations par utilisateur
- pas encore de paiement Revolut branché
- pas encore d’ajout automatique des générations après paiement

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

## Admin validé
Email admin :
- `skypieachannel@gmail.com`

L’admin sert à :
- suivre les ventes
- suivre les dépenses
- préparer les rapports trimestriels
- piloter l’activité depuis mobile

## Amélioration demandée par Cheikh
Cheikh veut maintenant que les rapports admin deviennent automatiques :
- rapport auto à l’ouverture de l’espace admin
- rapport auto après ajout d’une vente
- rapport auto après ajout d’une dépense
- affichage direct du trimestre courant sans action manuelle
- le bouton de génération doit devenir secondaire ou servir seulement à forcer une autre période

## Vision client
À terme :
- connexion client
- inscription client
- génération décomptée au moment du traitement final
- analyse consultable
- traitement consommant 1 génération
- paiement Revolut lié aux comptes

## Entreprise
- petite entreprise digitale créée
- activité légale lancée
- objectif : vendre l’usage de l’application

## Bugs importants déjà corrigés
- bug Vercel 404 causé par mauvaise racine / mauvais projet
- bug FFmpeg `makeup=0.8` corrigé
- traitement stems validé
- téléchargement final validé
- login admin validé

## Règle de travail importante
Cheikh est sur téléphone Android uniquement.
Toujours fournir :
- des fichiers complets
- prêts à coller
- sans micro-modifications compliquées
- avec le nom du fichier affiché seul quand demandé

## URLs à compléter
- Frontend Vercel : à compléter
- Backend Render : à compléter

## Prochain objectif
Améliorer la V10 admin avec rapports automatiques :
- rapport auto du trimestre courant
- mise à jour auto après vente
- mise à jour auto après dépense

## Étape suivante après ça
- connexion client
- inscription client
- générations par utilisateur
- paiement Revolut

## Reprise si conversation perdue
Si la conversation est perdue, repartir avec :
1. `PROJECT_STATE.md`
2. `NEXT_TASK.md`
3. `ASSISTANT_RULES.md`
4. les fichiers du frontend et du backend actuellement en ligne
