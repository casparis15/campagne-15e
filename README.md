# 📱 Application PWA - Campagne Porte à Porte

## 🎯 Qu'est-ce qu'une PWA ?

Cette application est une **Progressive Web App** qui fonctionne comme une vraie application mobile :
- ✅ Installable sur l'écran d'accueil
- ✅ Fonctionne hors ligne
- ✅ Données sauvegardées localement
- ✅ Expérience native mobile

## 📦 Fichiers inclus

- `campagne-porte-a-porte.html` - Application principale
- `manifest.json` - Configuration PWA
- `service-worker.js` - Gestion du cache hors ligne
- `icon-192.png` - Icône 192x192px
- `icon-512.png` - Icône 512x512px

## 🚀 Déploiement sur GitHub Pages (gratuit)

### Étape 1 : Créer un compte GitHub
1. Allez sur https://github.com
2. Créez un compte gratuit

### Étape 2 : Créer un nouveau repository
1. Cliquez sur le bouton vert "New" (Nouveau)
2. Nom du repository : `campagne-15e` (ou autre nom)
3. Cochez "Public" (ou "Private" si vous voulez limiter l'accès)
4. Cliquez sur "Create repository"

### Étape 3 : Upload les fichiers
1. Cliquez sur "uploading an existing file"
2. Glissez-déposez TOUS les fichiers :
   - campagne-porte-a-porte.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png
3. Cliquez sur "Commit changes"

### Étape 4 : Activer GitHub Pages
1. Allez dans "Settings" (Paramètres)
2. Dans le menu de gauche, cliquez sur "Pages"
3. Sous "Source", sélectionnez "main" branch
4. Cliquez sur "Save"
5. Attendez 1-2 minutes

### Étape 5 : Récupérer l'URL
Votre app sera accessible à : `https://votre-nom.github.io/campagne-15e/campagne-porte-a-porte.html`

## 📱 Installation sur téléphone

### Sur iPhone (Safari)
1. Ouvrez l'URL dans Safari
2. Appuyez sur le bouton "Partager" (carré avec flèche)
3. Faites défiler et appuyez sur "Sur l'écran d'accueil"
4. Appuyez sur "Ajouter"

### Sur Android (Chrome)
1. Ouvrez l'URL dans Chrome
2. Appuyez sur le menu (3 points)
3. Appuyez sur "Ajouter à l'écran d'accueil"
4. Confirmez

## 🔒 Sécurité et accès restreint

### Option 1 : URL secrète (simple)
- Ne partagez l'URL qu'avec les militants autorisés
- Sécurité par obscurité (comme un lien Google Drive privé)

### Option 2 : Repository privé (meilleure)
1. Rendez le repository "Private" sur GitHub
2. Invitez uniquement les personnes autorisées
3. Elles devront se connecter à GitHub pour y accéder

### Option 3 : Protection par mot de passe
- GitHub Pages ne supporte pas l'authentification native
- Il faudrait utiliser un autre service (Netlify, Vercel)

## 🌐 Alternative : Netlify (plus simple que GitHub)

1. Allez sur https://www.netlify.com
2. Créez un compte gratuit
3. Glissez-déposez le dossier contenant tous les fichiers
4. C'est en ligne ! URL fournie instantanément
5. Vous pouvez personnaliser l'URL

## 💾 Données et stockage

- Toutes les données sont sauvegardées dans le **localStorage** du navigateur
- Les données restent **sur l'appareil** de chaque utilisateur
- **Aucune donnée n'est envoyée à un serveur**
- Pour centraliser les données, chaque militant devra exporter ses données

## 🆘 Support

Si vous avez besoin d'aide pour :
- Le déploiement
- L'ajout d'une fonction d'export de données
- La création d'une version avec authentification réelle
- Autre chose

N'hésitez pas à demander !

## 📊 Prochaines étapes suggérées

1. ✅ Déployer la PWA
2. ⬜ Ajouter une fonction d'export CSV/Excel
3. ⬜ Créer un système de synchronisation centralisé
4. ⬜ Ajouter des statistiques de campagne
