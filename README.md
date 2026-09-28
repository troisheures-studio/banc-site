# Site public de BANC

Une seule page pour l'instant : la politique de confidentialité (`index.html`,
copie de `confidentialite.html`), en français et en anglais, exigée par App Store
Connect sous forme d'URL publique.

## Mise en ligne sur GitHub Pages (une fois)

1. Sur github.com : « New repository », nom `banc-site`, public, sans README.
2. Ici, dans ce dossier :
   git remote add origin https://github.com/<ton-compte>/banc-site.git
   git push -u origin main
3. Sur GitHub : Settings → Pages → Source « Deploy from a branch », branche `main`,
   dossier `/ (root)` → Save. Une minute plus tard, la page est à
   https://<ton-compte>.github.io/banc-site/
4. Coller cette adresse dans App Store Connect (« URL de la politique de
   confidentialité » et « URL d'assistance »).

Pour modifier la politique : éditer les deux fichiers, `git commit`, `git push`.
