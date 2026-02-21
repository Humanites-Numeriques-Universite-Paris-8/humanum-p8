# humanum-p8

Site Web du département **Humanités Numériques** de l'Université Paris 8 Vincennes-Saint-Denis — [humanum-p8.fr](https://humanum-p8.fr).

## À propos

Ce site est construit avec [Quarto](https://quarto.org) et déployé automatiquement sur GitHub Pages.

## Structure du site

| Fichier | Page |
|---------|------|
| `index.qmd` | Accueil |
| `formation.qmd` | Formations (Licence, Master, formation continue) |
| `recherche.qmd` | Recherche (axes, projets, laboratoires, publications) |
| `equipe.qmd` | Équipe enseignante et de recherche |
| `actualites.qmd` | Actualités et événements |
| `contact.qmd` | Contact et informations pratiques |
| `mentions-legales.qmd` | Mentions légales |
| `accessibilite.qmd` | Déclaration d'accessibilité |

## Développement local

### Prérequis

- [Quarto](https://quarto.org/docs/get-started/) ≥ 1.6

### Construire le site

```bash
quarto render
```

### Prévisualiser en local

```bash
quarto preview
```

## Déploiement

Le site est déployé automatiquement sur [GitHub Pages](https://pages.github.com) à chaque push sur la branche `main` via le workflow `.github/workflows/deploy.yml`.
