# Accordeur multi-instruments

Accordeur web pour guitare, Drop D, basse 4 et 5 cordes, ukulélé (soprano et baryton), mandoline, banjo, violon, plus un mode chromatique. Notes de référence et détection par micro. Fonctionne hors connexion une fois chargé et s'installe sur l'écran d'accueil du téléphone.

## Publier sur GitHub Pages (sans ligne de commande)

1. Sur github.com, crée un dépôt public, par exemple `accordeur`.
2. Clique sur **Add file > Upload files** et glisse tout le contenu de ce dossier : `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`.
3. Clique sur **Commit changes**.
4. Va dans **Settings > Pages**. Sous *Build and deployment*, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Après une minute environ, l'accordeur est en ligne sur `https://TON-PSEUDO.github.io/accordeur/`.

## Installer sur le téléphone

- iPhone (Safari) : bouton Partager, puis **Sur l'écran d'accueil**.
- Android (Chrome) : menu ⋮, puis **Installer l'application** ou **Ajouter à l'écran d'accueil**.

Au premier clic sur « Activer le micro », le navigateur demande l'autorisation : accepte. Le micro ne fonctionne qu'en HTTPS (ce que fournit GitHub Pages) ou en local sur `localhost`.

## Autres hébergements gratuits

- **Netlify Drop** (app.netlify.com/drop) : glisse le dossier dans la page, le lien est immédiat.
- **Cloudflare Pages** ou **Vercel** : connecte le dépôt GitHub, aucun réglage de build nécessaire.

## Tester sur ton ordinateur

Depuis ce dossier : `python3 -m http.server 8000`, puis ouvre `http://localhost:8000`.
