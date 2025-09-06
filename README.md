# Pack GitHub Pages – Sans Actions

## Utilisation
1. Créez un dépôt **public** sur GitHub.
2. Uploadez **tout le contenu** de ce pack à la racine du dépôt (y compris le dossier `docs/`).
3. Dans **Settings → Pages** : sélectionnez *Deploy from a branch* → Branch **main** / Folder **/docs**.
4. Ajoutez vos documents dans `PDF/`, `Docs/`, `Images/`, `Meta/` (ou ailleurs).  
   ➜ L’index se mettra automatiquement à jour (il lit l’arborescence via l’API GitHub côté navigateur).

⚠️ Attention : fonctionne uniquement pour un dépôt **public** (API GitHub). Pour un dépôt privé, il faut la version avec Actions.
