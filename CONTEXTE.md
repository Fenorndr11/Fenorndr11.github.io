# CONTEXTE — Avancement du projet « Portfolio fusionné »

_Dernière mise à jour : 12/10/2026_

## Objectif
Fusionner deux portfolios existants en un seul site statique, y ajouter les expériences vécues avec Claude, et le publier sur GitHub Pages.

## Ce qui a été fait
1. **Analyse** des deux archives :
   - `portfolio_fenotiana` : meilleur design (cartes de projets illustrées, thème vert/lime) → **retenu comme base**.
   - `portfolio_randriamarojaona_fenotiana` : contenu complémentaire (algorithmes de graphes, chronologie, ton plus académique) → **contenu intégré**.
2. **Fusion** : un seul site (`index.html`, `style.css`, `script.js`, `favicon.svg`, `.nojekyll`, `README.md`).
3. **Expériences ajoutées** (13 projets au total) : Asterisk/VoIP (AGI, SIP trunk), ConnecteoAPP (pôle Backend), TestaSon (ESP32 → Raspberry Pi), Supabase/PostgreSQL, DNS/BIND9 + routage, graphes Python (Erdős–Rényi, Bron–Kerbosch, Neo4j), Qt/C++, tableau de bord photorésistance, OpenStreetMap/Neo4j, laboratoire Parrot OS, HackTheBox + stack SOC, n8n, présentations CPU/GPU, fondations web.
4. **Sections** : accueil, profil, projets, compétences (6 domaines), parcours (chronologie), « en ce moment », contact.
5. **Vérifications** : rendu testé sur ordinateur (1366 px) et mobile (390 px), aucun débordement, aucune erreur console.

## Décisions et critiques
- Barres de niveau en pourcentage **supprimées** : chiffres inventés, non défendables en entretien. Remplacées par des listes d'outils réellement utilisés.
- Aucune adresse IP interne, mot de passe ni donnée sensible publiée.
- Statut honnête affiché sur chaque projet (prototype, laboratoire, en cours).
- Mémoire de dissertation « Translation and Interpreting Madagascar » non incluse (ne semble pas être un projet informatique personnel).

## À faire par Feno (je ne peux pas le faire à ta place)
1. Remplacer dans `index.html` : `TON-EMAIL@exemple.com` et `https://github.com/TON-PSEUDO`.
2. Créer le dépôt public `TON-PSEUDO.github.io`, téléverser tous les fichiers (dont `.nojekyll`), activer Settings → Pages → branche `main` / root.
3. Relire les descriptions et corriger tout ce qui est inexact.

## Pistes ensuite
- Ajouter des captures d'écran et des liens vers les dépôts GitHub de chaque projet.
- Vérifier la formation exacte (établissement) avant de l'ajouter.
