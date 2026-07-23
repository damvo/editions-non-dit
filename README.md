# Site vitrine — Éditions Non-Dit

Site statique prêt pour GitHub Pages, conçu pour la vérification d'une application Pinterest Developer.

## Contenu
- `index.html` — page vitrine (à propos, collection, Pinterest, contact)
- `privacy.html` — politique de confidentialité (couvre l'usage de l'API Pinterest, requis par Pinterest)
- `terms.html` — conditions d'utilisation & mentions légales
- `404.html` — page d'erreur
- `assets/style.css`, `assets/logo.svg`
- `robots.txt`, `sitemap.xml`, `.nojekyll`

## AVANT DE PUBLIER — 2 remplacements obligatoires

1. Remplace partout `damvo` par ton nom d'utilisateur GitHub réel.
   Fichiers concernés : `index.html`, `privacy.html`, `terms.html`, `robots.txt`, `sitemap.xml`.
   (Cherche/remplace `damvo.github.io/editions-non-dit`.)

2. Si tu nommes le dépôt autrement que `editions-non-dit`, adapte aussi ce segment d'URL.

Les liens Etsy (`etsy.com/shop/EditionsNonDit`), Pinterest (`pinterest.com/editionsnondit`) et courriel sont déjà renseignés — vérifie qu'ils sont exacts.

## Publication sur GitHub Pages

### Option A — interface web (sans ligne de commande)
1. Va sur https://github.com/new et crée un dépôt public nommé `editions-non-dit`.
2. Sur la page du dépôt : `Add file` > `Upload files`. Glisse **tout le contenu** de ce dossier (les fichiers, pas le dossier parent), y compris le dossier `assets` et le fichier `.nojekyll`. Commit.
3. `Settings` > `Pages`. Sous *Source*, choisis `Deploy from a branch`, branche `main`, dossier `/ (root)`. Save.
4. Attends 1–2 min. L'URL s'affiche : `https://damvo.github.io/editions-non-dit/`.

### Option B — en ligne de commande
```bash
cd editions-non-dit-site
git init
git add .
git commit -m "Site vitrine Éditions Non-Dit"
git branch -M main
git remote add origin https://github.com/damvo/editions-non-dit.git
git push -u origin main
```
Puis active Pages via `Settings > Pages` comme à l'étape A.3.

## Vérification Pinterest Developer
Dans ta configuration d'application Pinterest :
- **Website / App URL** : `https://damvo.github.io/editions-non-dit/`
- **Privacy policy URL** : `https://damvo.github.io/editions-non-dit/privacy.html`
- **Terms / conditions URL** : `https://damvo.github.io/editions-non-dit/terms.html`

Assure-toi que le site est bien en ligne (URL accessible) AVANT de soumettre la vérification.
