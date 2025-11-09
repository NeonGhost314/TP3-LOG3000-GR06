# Module Templates

## Objectif  
Expliquer les vues HTML que Flask rend pour afficher l’interface de la calculatrice.  
Tout ce qui se trouve dans ce dossier définit ce que les utilisateurs voient lorsqu’ils interagissent avec l’application.

## Fichiers principaux  
- `index.html` : Page unique de la calculatrice contenant la mise en page, les boutons, le champ d’affichage et de petits scripts JavaScript intégrés pour ajouter les chiffres et opérateurs.

## Dépendances et hypothèses  
- Servi via la fonction `render_template` de Flask dans `app.py` ; tout nouveau modèle doit y être référencé.  
- Dépend des ressources situées dans le dossier `static/` (par exemple `style.css`) à l’aide de `url_for('static', filename=...)`.  
- Écrit en HTML simple ; aucun héritage de modèle ni framework n’est encore configuré.

## Conseils d’utilisation  
- Lors de l’ajout d’une nouvelle page, suivez la même structure que l’existante et mettez à jour `app.py` pour lui associer une route.  
- Gardez les scripts intégrés au minimum ; déplacez la logique réutilisable dans des fichiers statiques dédiés si elle devient plus complexe.