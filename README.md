# starter-cuillere
Un Starter pour Astrojs en css avec Better auth

## Installation

Ce projet est déjà configuré avec toutes les dépendances nécessaires. Pour commencer :

```bash
npm install
```

## Dépendances incluses

### Production
- **Astro.js** (v5.14.1) - Framework web moderne
- **Astro Icon** avec les bibliothèques d'icônes :
  - `@iconify-json/mdi` - Material Design Icons
  - `@iconify-json/circle-flags` - Circle Flags
- **Astro Font** - Gestion des polices optimisée
- **Prisma** avec `@prisma/client` - ORM pour PostgreSQL
- **Better-Auth** - Système d'authentification
- **NodeMailer** - Envoi d'emails

### Développement
- `prisma` - CLI Prisma
- `tsx` - Exécuteur TypeScript
- `@types/nodemailer` - Types TypeScript pour NodeMailer

## Scripts disponibles

```bash
# Démarrer le serveur de développement
npm run dev

# Construire pour la production
npm run build

# Prévisualiser la version de production
npm run preview
```

## Structure du projet

```
/
├── src/
│   └── pages/
│       └── index.astro
├── public/
├── astro.config.mjs
├── tsconfig.json
└── package.json
```
