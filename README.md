# UMS RH — Gestion Employés & Congés

Application web de gestion des ressources humaines développée pour UMS.

## Fonctionnalités

- 👥 Gestion complète des employés (ajout, modification, suppression)
- 📋 Demandes de congés avec calcul automatique des jours ouvrés
- ⏳ Suivi des congés en cours en temps réel
- 📊 Classement par priorité, durée et solde
- 📅 Calendrier visuel des congés
- 📈 Tableau de bord avec statistiques
- 💾 Sauvegarde automatique dans le navigateur (localStorage)
- 🖨️ Génération de fiches et attestations de congé (PDF)
- 📊 Export Excel et PDF
- 🎨 4 thèmes visuels (Ocean, Violet, Clair, Forêt)
- 🔥 Compatible Firebase pour synchronisation multi-appareils

## Utilisation

Ouvrez simplement le fichier `index.html` dans votre navigateur,  
ou accédez à l'URL Netlify de déploiement.

Au premier lancement, cliquez **"Mode local (sans Firebase)"**.

## Configuration Firebase (optionnel)

Pour synchroniser les données entre plusieurs appareils / collègues :

1. Créez un projet sur [console.firebase.google.com](https://console.firebase.google.com)
2. Activez **Authentication → Email/Password**
3. Activez **Firestore Database** (mode test)
4. Copiez votre config Firebase dans `index.html` (section `FB_CFG`)
5. Redéployez sur Netlify

## Déploiement Netlify

Ce dépôt est prêt à être déployé sur Netlify :
- Fichier principal : `index.html`
- Aucune dépendance serveur requise
- Aucune commande de build nécessaire

## Version

v3.0 — Persistance localStorage complète

