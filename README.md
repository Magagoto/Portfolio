# Portfolio (GitHub Pages)

Ce dossier est prêt à être publié en site **GitHub Pages**.

## Fichiers
- `index.html` : page d’accueil
- `contact.html` : page contact
- `Image couverture .jpg` : image
- `Portfolio.pdf` : PDF

## Publication (site “user”, URL propre)
### Option A — "Project site" (repo classique, ex: `Magagoto/Portfolio`)
1. Dans le repo, va dans **Settings → Pages**.
2. **Source** : branche `main` + dossier `/ (root)`.
3. Attends que GitHub affiche l’URL du site.

L’URL sera en général : `https://<ton_pseudo_github>.github.io/<nom_du_repo>/`

### Option B — "User site" (URL à la racine)
1. Crée un repository nommé **`<ton_pseudo_github>.github.io`** (exactement).
2. Dans **Settings → Pages**, source `main` + `/ (root)`.
3. Push ces fichiers à la racine.

L’URL sera : `https://<ton_pseudo_github>.github.io/`

## Domaine personnalisé (plus tard)
Quand tu auras acheté ton domaine :
- Repo → **Settings → Pages → Custom domain**
- Ajoute les enregistrements DNS chez ton registrar (A + CNAME) puis active **Enforce HTTPS**.

Note : si tu utilises un domaine personnalisé, GitHub Pages crée/attend souvent un fichier `CNAME`.
Si le domaine (DNS) n’est pas correctement configuré, le site peut sembler “indisponible” ou rediriger vers un domaine cassé.
