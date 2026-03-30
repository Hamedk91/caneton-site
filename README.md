# CANETON — Site vitrine

## Structure
```
caneton/
├── index.html        → Page d'accueil
├── collection.html   → Grille de produits + filtres
├── produit.html      → Fiche produit détaillée
├── panier.html       → Panier & commande
├── contact.html      → Formulaire RDV & contact
├── css/style.css     → Styles globaux
├── js/main.js        → Panier, interactions
├── images/           → Tes photos produits
│   ├── veste-kuba.png
│   └── veste-ashanti.png
└── vercel.json       → Config hébergement Vercel
```

## Ajouter des photos
Dépose tes nouvelles images dans le dossier `images/` et mets à jour les références dans les fichiers HTML.

## Déploiement sur Vercel (5 minutes)

### Étape 1 — Créer un dépôt GitHub
1. Va sur https://github.com et crée un compte si besoin
2. Clique "New repository" → nomme-le `caneton-site`
3. Upload tous les fichiers du dossier `caneton/`

### Étape 2 — Déployer sur Vercel
1. Va sur https://vercel.com et connecte-toi avec GitHub
2. Clique "Add New Project"
3. Sélectionne le repo `caneton-site`
4. Clique "Deploy" (aucune config nécessaire)
5. Ton site est en ligne en 1 minute ! ✅

### Étape 3 — Nom de domaine custom (optionnel)
Dans Vercel → Settings → Domains → ajoute `caneton.fr`

## Ajouter un nouveau produit
1. Ajoute l'image dans `images/`
2. Dans `collection.html` : copie un bloc `.col-pcard` et adapte les infos
3. Dans `produit.html` : ajoute une entrée dans l'objet `products`
4. Commit & push → Vercel redéploie automatiquement

## Fonctionnalités
- ✅ Navigation responsive (mobile + desktop)
- ✅ Panier persistant (localStorage)
- ✅ Filtres collection par catégorie
- ✅ Page produit avec galerie & sélecteur de taille
- ✅ Formulaire de contact / RDV avec tabs
- ✅ Animations au scroll (reveal)
- ✅ Toast notifications
- ✅ Hover effects sur les produits
