# pomponlabs-site

Site web de **Pompon Labs** : page d'accueil qui liste toutes les applis disponibles.

Publié sur https://pomponlabs.com via GitHub Pages. Ce dépôt ne contient que le site, pas le code des applis.

## Contenu

- `index.html` : la page d'accueil (Botz, Popote, Zoralia) ; style « atelier coloré »
- `style.css` : styles et animations (désactivées si l'appareil demande moins de mouvement)
- `fonts/` : Bungee et Fredoka (les mêmes que Botz)
- `logo.svg`, `logo.png` : la mascotte Pompon
- `botz.png`, `popote.png`, `zoralia.png` : icônes des applis
- `icon.svg`, `favicon.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` : icônes du site
- `CNAME` : domaine `pomponlabs.com`

## Ajouter une appli

Dupliquer un bloc `<a class="app" …>` dans `index.html` (même structure : icône, nom, description, bouton) avec ses deux couleurs `--c1` et `--c2` et sa couleur d'ombre `--dk`. La case en pointillés « La suite arrive bientôt… » peut alors être supprimée ou gardée.

## Contact

contact@pomponlabs.com
