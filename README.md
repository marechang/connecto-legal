# connecto-legal

Pages légales publiques de l'application **Connecto** (coach sportif IA), éditée par STACKONE.

Site statique déployé sur Vercel — l'URL de production est fournie aux stores (App Store, Google Play) pour la politique de confidentialité et les futures pages légales.

## Pages

| Fichier | URL | Contenu |
|---|---|---|
| `index.html` | `/` | Politique de confidentialité |

## Ajouter une nouvelle page légale

1. Créer un fichier HTML à la racine (ex : `cgu.html`, `mentions-legales.html`).
2. Réutiliser la structure `<style>` de `index.html` pour rester cohérent visuellement.
3. Commit + push : Vercel redéploie automatiquement.
4. La page sera accessible à `https://<domaine-vercel>/cgu` (grâce à `cleanUrls` dans `vercel.json`).

## Déploiement

Site statique — aucun build. Vercel sert les fichiers HTML tels quels.

- Framework : *Other* (static HTML)
- Build command : *(vide)*
- Output directory : *(vide, racine)*

## Contact

STACKONE — mare.chang@live.fr
