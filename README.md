# Dial In Espresso

PWA perso (iPhone) pour régler espresso et café filtre : journal rapide, minuteur guidé, roue du goût → correction du prochain essai, stock de grains avec fraîcheur.

Équipement par défaut : Eureka Mignon Specialita (micrométrique, pas en graduations), Profitec Pro 500 (échangeur thermique).

## Fichiers
- `index.html` — toute l'app (HTML/CSS/JS, données en `localStorage`, clé `dialin-v1`)
- `manifest.json`, `sw.js` — installation PWA et hors ligne
- `icons/` — icônes 180/192/512

## Tester sur PC
Ouvrir `index.html` dans un navigateur (le service worker exige http/https, le reste marche en `file://`).

## Installer sur iPhone
1. Héberger en HTTPS (GitHub Pages).
2. Ouvrir l'URL dans Safari → Partager → « Sur l'écran d'accueil ».
3. Exporter une sauvegarde JSON régulièrement (Réglages).

Mise à jour : incrémenter `VERSION` dans `sw.js`.
