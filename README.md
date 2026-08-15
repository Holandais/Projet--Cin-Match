# CineMatch

Application front-end consommant l'API TMDB pour afficher les films en tendance et permettre la recherche.

- Dossier : `projet 2`
- Description : recherche, affichage des tendances, modal de détails, favoris persistants (localStorage).

Prérequis
- Clé API TMDB (obligatoire)
- Navigateur moderne
- Serveur HTTP local pour tester

Obtention de la clé TMDB
1. Inscrivez-vous sur https://www.themoviedb.org/ et créez une clé API.
2. Ouvrez `projet 2/script.js` et remplacez la constante `TMDB_API_KEY` par votre clé.

Lancer
```bash
python -m http.server 8000
```
Puis : `http://localhost:8000/projet%202/index.html`

Fichiers
- `index.html` — interface et modal
- `style.css` — styles
- `script.js` — fetch TMDB (trending/search), modal, favoris

Remarques
- Les favoris sont stockés dans `localStorage` sous une clé dédiée.
- Vérifiez la console du navigateur pour les erreurs réseau ou clés manquantes.
