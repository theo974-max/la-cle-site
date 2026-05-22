# La Clé — Site web

Studio de commerce digital basé à Nîmes.

## Structure

- `index.html` — accueil (vidéo hero + contact)
- `services.html` — services & devis vivant
- `realisations.html` — projets réalisés
- `equipe.html` — Aymen & Théo
- `defis.html` — défis sport
- `faq.html` — questions fréquentes
- `merci.html` — page de confirmation des formulaires
- `assets/` — vidéo, images, favicon (NE PAS séparer des pages HTML)
- `netlify.toml`, `robots.txt`, `sitemap.xml` — config déploiement & SEO

## Déploiement

Glisser le dossier complet sur Netlify ou Vercel.
Les formulaires (devis, défi) fonctionnent automatiquement via Netlify Forms.

## Important

Le dossier `assets/` doit toujours rester au même niveau que les fichiers `.html`,
sinon les images et la vidéo ne s'affichent pas.
