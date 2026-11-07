# Mahdi

Site statique professionnel déployé sur Vercel.

## Structure

```
mahdi/
├── index.html          # Page d'accueil
├── admin.html          # Page d'administration
├── vercel.json         # Configuration de déploiement Vercel
├── .gitignore          # Fichiers ignorés par Git
└── README.md           # Ce fichier
```

## Déploiement

Ce projet est déployé automatiquement sur Vercel à chaque push sur la branche `main`.

### Déploiement manuel (CLI)

```bash
vercel --prod --yes
```

### Variables d'environnement

Aucune variable d'environnement requise pour ce site statique.

### Accès

Le site est accessible publiquement sans authentification.

## Maintenance

- **Rollback** : `vercel promote <deployment-id> --prod`
- **Logs** : `vercel logs --follow`
- **Inspect** : `vercel inspect <deployment-url>`
