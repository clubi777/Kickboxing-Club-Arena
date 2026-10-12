# Kickboxing Club Arena — Prototype 0.1

Prototype React + Vite autonome, en français.

## Démarrage

1. Importer le ZIP dans StackBlitz (projet Vite) ou décompresser en local.
2. `npm install`
3. `npm run dev`

## Jouable

- Salle personnelle isométrique stylisée, volontairement rustique
- Boutique d'équipements avec placement automatique
- Entraînements, énergie, progression de statistiques et techniques
- Usure et réparation du sac de frappe
- Club séparé : le joueur commence sans club et peut créer un club local
- Sauvegarde automatique dans le navigateur (localStorage)

## Limites connues

- Graphismes **prototypés en CSS**, pas encore les illustrations haute définition des maquettes de référence.
- Pas de serveur ni de synchronisation multijoueur : le club créé reste local à ce navigateur.
- Les entraînements et prix sont provisoires, à équilibrer.
- Pas encore de combats simulés, d'authentification ou de base Neon.

## Prochaine étape

Remplacer le rendu CSS par des assets isométriques découpés, ajouter les combats simulés, puis l'API backend et la persistance Neon.
