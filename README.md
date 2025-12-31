# GENERATEUR-B2B

Static React (Babel) page for the Solaire Facile generator. Everything runs client-side with CDN React, Tailwind CDN, and Mapbox GL loaded lazily from the component.

## Utilisation locale

1. Ouvrir `index.html` dans le navigateur (double-clic ou `npx serve .`).
2. Remplacer le token Mapbox si besoin : définir `window.MAPBOX_TOKEN` dans la console ou éditer `MAPBOX_TOKEN` dans le script.

## Déploiement GitHub Pages

Le dépôt est prêt à être servi depuis la branche `main` (racine) ou via Pages. Si Pages n'est pas encore activé : Settings → Pages → Deploy from a branch → `main` / `/ (root)`, ou laisser le workflow GitHub Actions (optionnel) pousser vers `github-pages`.
