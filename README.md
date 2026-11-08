# Registre d’entretien jardin

Application web (PWA) : calendrier d’entretien des plantes du jardin, avec recherche, ajout de plantes et engrais par mois. Fonctionne sur iPhone et Mac, et hors connexion après la première ouverture.

## Mise en ligne avec GitHub Pages
1. Crée un dépôt GitHub (par exemple `registre-jardin`) et envoie-y tout le contenu de ce dossier (`index.html`, `manifest.json`, `sw.js`, `icons/`).
2. Dans le dépôt : Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. L’adresse sera `https://TON-PSEUDO.github.io/registre-jardin/`.

## Installation
- iPhone : ouvre l’adresse dans Safari → Partager → « Sur l’écran d’accueil ».
- Mac : ouvre l’adresse dans Safari → Fichier → « Ajouter au Dock ».

## Données
Les plantes ajoutées sont enregistrées sur l’appareil, dans l’application installée. Une mise à jour du code sur GitHub ne les efface pas. « Exporter » et « Importer » servent à sauvegarder ou à transférer ces plantes d’un appareil à l’autre.

## Mettre à jour l’application
Remplace `index.html` dans le dépôt. Pour forcer le rechargement chez toi, change le numéro de version `jardin-v2` dans `sw.js`.
