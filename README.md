# Portfolio de Fenotiana Randriamarojaona

Site statique (HTML, CSS, un peu de JavaScript), prêt pour GitHub Pages. Aucune étape de compilation n'est nécessaire.

## Fichiers
- `index.html` : contenu du site
- `style.css` : design responsive
- `script.js` : année automatique du pied de page
- `favicon.svg` : icône de l'onglet
- `.nojekyll` : dit à GitHub Pages de publier les fichiers tels quels

## Avant de publier : 2 liens à remplacer
Dans `index.html`, tout en bas de la section Contact :
1. `mailto:TON-EMAIL@exemple.com` → ton adresse e-mail réelle
2. `https://github.com/TON-PSEUDO` → l'adresse de ton profil GitHub

## Prévisualiser en local (Parrot OS)
Depuis ce dossier, lance un petit serveur web (`python3 -m http.server 8000`), puis ouvre `http://localhost:8000`.

## Publier sur GitHub Pages
1. Crée un dépôt **public** nommé exactement `TON-PSEUDO.github.io`.
2. Envoie tous les fichiers (y compris `.nojekyll`) à la racine du dépôt, sur la branche `main`.
3. Ouvre **Settings → Pages**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après 1 à 10 minutes, le site est disponible sur `https://TON-PSEUDO.github.io/`.

Documentation officielle : https://docs.github.com/en/pages/quickstart
