# Programme BBX

Application web de suivi d'entraînement (minuteurs de repos, séries, poids par exercice, abdos), installable sur iPhone avec son icône BBX.

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (par exemple `bbx-app`).
2. Envoie tout le contenu de ce dossier à la racine du dépôt (**Add file → Upload files**, ou `git push`).
3. Dans le dépôt : **Settings → Pages → Build and deployment**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, l'app est en ligne à l'adresse `https://TON-PSEUDO.github.io/bbx-app/`.

## Installer sur iPhone (icône BBX)

1. Ouvre l'adresse ci-dessus dans **Safari**.
2. Touche **Partager** puis **Sur l'écran d'accueil**.
3. L'app s'ouvre ensuite en plein écran, avec l'icône BBX.

Si tu avais déjà ajouté l'app avant, supprime l'ancienne icône puis ajoute-la de nouveau.

## Contenu

- `index.html` : l'application
- `manifest.webmanifest` : nom, couleurs et icônes de l'app
- `sw.js` : fonctionnement hors-ligne (toujours la dernière version quand le réseau est là)
- `icons/` : icône BBX en 1024, 512, 192, 180, 167, 152 et 120 px

Tes poids et séries sont enregistrés sur l'appareil (stockage local du navigateur).
