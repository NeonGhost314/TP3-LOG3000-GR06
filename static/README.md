# Module Static

## Objectif  
Stocker les feuilles de style et autres ressources que Flask sert directement au navigateur.  
Ces fichiers contrôlent l’apparence et l’ergonomie de la calculatrice sans modifier la logique du serveur.

## Fichiers principaux  
- `style.css` : Feuille de style principale responsable de la mise en page, de la typographie et du style des boutons de la calculatrice.

## Dépendances et hypothèses  
- Référencée par les modèles via `url_for('static', filename='style.css')` ; les noms de fichiers doivent rester cohérents.  
- Aucun outil de build (Webpack, Sass, etc.) n’est configuré — les ressources doivent rester en CSS/JS simples.  
- Il peut être nécessaire de vider le cache du navigateur après des modifications importantes du style.

## Conseils d’utilisation  
- Gardez les sélecteurs limités au balisage de la calculatrice pour éviter d’éventuels conflits à l’avenir.  
- Ajoutez ici toute nouvelle ressource statique et référencez-la dans les modèles correspondants afin que Flask puisse les servir correctement.