# JOURNAL

## 2026-10-20
- Choix PWA plutôt qu'app native : pas de Mac, usage perso, pas d'expiration de signature. Perte : Bluetooth (balances) non dispo dans Safari.
- v1 écrite : un seul `index.html`, `localStorage`, service worker réseau-d'abord.
- Fraîcheur : < 5 j repos, 5–35 j idéal, > 35 j déclin ; congelé = pause.
- Balance MAVO Lumicurve : aucun Bluetooth/app trouvé + Safari iOS sans Web Bluetooth → lecture de l'écran par photo IA.
- IA : appel direct `api.anthropic.com` depuis le navigateur (`anthropic-dangerous-direct-browser-access`), modèle `claude-sonnet-5-5`, photo réduite à 1280 px.
- Clé API : `localStorage['dialin-cle']`, saisie par l'utilisateur dans Réglages, jamais dans le code ni dans l'export JSON (le site sera public).
- Testé sans clé : remplissage balance/sac, contexte galette, diagnostic sauvé au journal. Appel API réel pas encore testé.
