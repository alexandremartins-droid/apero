# Visionneuse HTML – GitHub Ready

## Structure à conserver
- `index.html`
- `pages.json`
- `histoire_tour.pdf`
- `assets/pages/*.jpg`
- `assets/thumbs/*.jpg`

## Important
Ne déplacez pas uniquement les images à la racine.
La structure des dossiers doit être conservée telle quelle, sinon les chemins relatifs ne correspondront plus.

## Utilisation locale
Ouvrez `index.html` directement dans le navigateur.
Cette version n'utilise plus `fetch('pages.json')`, donc elle fonctionne aussi en local via `file://`.

## Upload sur GitHub
1. Créez un dépôt GitHub.
2. Uploadez **tout le contenu** du dossier à la racine du dépôt.
3. Vérifiez que `index.html` est bien à la racine.
4. Laissez le dossier `assets` intact.
5. Activez GitHub Pages si vous voulez une URL publique.

## GitHub Pages
- Settings > Pages
- Branch: `main`
- Folder: `/ (root)`

Le site sera ensuite servi avec `index.html` comme page d'accueil.