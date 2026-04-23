# Stéphane-IA - Site Vitrine

Bienvenue sur le dépôt du site marketing de **Stéphane-IA**, l'application de fitness Social-First propulsée par l'intelligence artificielle.

## Liens Utiles
- **Site Live :** [https://stephane.fit](https://stephane.fit)
- **Lancer l'Application :** [https://app.stephane.fit](https://app.stephane.fit)

---

## À propos de Stéphane-IA
Stéphane-IA n'est pas qu'un simple tracker de musculation, c'est un écosystème complet conçu pour les passionnés et les seniors actifs.

### Stéphane : Le Coach IA
Au cœur de l'expérience, **Stéphane** analyse les performances de l'utilisateur, ses records personnels (PR) et lui propose une surcharge progressive adaptée, le tout avec un ton bienveillant et professionnel.

### Fonctionnalités Clés
- **Saisie en langage naturel :** Notez vos séances comme vous les parlez.
- **Social Feed :** Partagez vos exploits et recevez des Kudos de la communauté.
- **Mémoire Longue :** Analyse des tendances sur 12 semaines pour éviter la stagnation.
- **Green IT & Privacy :** Optimisation de la consommation énergétique (CO2) et respect total du RGPD.

---

## Tech Stack

- **Framework :** [React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/)
- **Build Tool :** [Vite](https://vitejs.dev/)
- **Styling :** [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons :** [Lucide React](https://lucide.dev/)
- **Déploiement :** [Cloudflare Pages](https://pages.cloudflare.com/)

## Déploiement (Cloudflare Pages)

Le site est déployé sur **Cloudflare Pages** avec le domaine personnalisé `stephane.fit`.

**Configuration du build :**
| Paramètre | Valeur |
|---|---|
| Build command | `npm run build` |
| Build output directory | `dist` |
| Node.js version | 18+ |

Les fichiers `public/_redirects` et `public/_headers` gèrent respectivement le routing SPA et la mise en cache des assets sur le CDN Cloudflare.

---

## Engagement Green IT & Confidentialité
Le projet intègre des mesures de transparence sur l'impact carbone des requêtes IA et garantit qu'aucune donnée de santé n'est vendue ou utilisée à des fins publicitaires.
