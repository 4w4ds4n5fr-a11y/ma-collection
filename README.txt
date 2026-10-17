# Ma Collection — Enchères & Maison

## Fichiers
- `index.html` : le jeu
- `manifest.json` : informations d'installation
- `sw.js` : cache pour un usage hors connexion après le premier chargement
- `icon-192.png` et `icon-512.png` : icônes

## Pour l'installer sur un téléphone
Une PWA doit être servie par HTTPS (ou localhost) pour que l'installation et le mode hors connexion fonctionnent correctement. Il ne suffit pas d'ouvrir `index.html` depuis les fichiers du téléphone.

### Méthode simple : GitHub Pages
1. Sur un ordinateur, crée un compte ou connecte-toi à GitHub.
2. Crée un nouveau dépôt public, par exemple `ma-collection`.
3. Envoie les cinq fichiers du dossier dans le dépôt, à la racine.
4. Dans le dépôt, ouvre **Settings → Pages**.
5. Choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Attends que GitHub fournisse l'adresse HTTPS de ton site.
7. Ouvre cette adresse sur ton téléphone :
   - **iPhone (Safari)** : bouton Partager → **Sur l'écran d'accueil** → Ajouter.
   - **Android (Chrome)** : menu ⋮ → **Installer l'application** ou **Ajouter à l'écran d'accueil**.

Le jeu est local à l'appareil : les parties ne sont pas synchronisées entre plusieurs téléphones. Pour jouer ensemble, utilisez le même téléphone et passez-le entre les joueurs. Une version en ligne multi-appareils demanderait un serveur.
