# Portfolio géomatique

Ce dossier contient un portfolio statique prêt à être publié avec GitHub Pages.

## Structure

- `index.html` : page d'accueil
- `style.css` : apparence du site
- `projets/` : pages détaillées des projets
- `images/` : captures et illustrations
- `documents/` : PDF et autres livrables

## Personnalisation

1. Remplace `Prénom Nom` dans `index.html`
2. Modifie les textes des cartes
3. Duplique une carte pour ajouter un projet
4. Duplique une page dans `projets/` pour créer une nouvelle fiche projet
5. Ajoute tes images dans `images/`
6. Ajoute tes PDF dans `documents/`
7. Remplace les liens `href` dans les pages projet

## Ajouter une image de projet

Dans une page projet, remplace le bloc `preview-placeholder` par :

```html
<img src="../images/mon-projet.png" alt="Aperçu du projet">
```

Le lien autour de l'image peut pointer vers un PDF, une StoryMap, une application ArcGIS Online, un dépôt GitHub ou toute autre URL.

## Publication avec GitHub Pages

1. Crée un nouveau dépôt GitHub
2. Ajoute tout le contenu de ce dossier à la racine du dépôt
3. Ouvre les paramètres du dépôt
4. Va dans `Pages`
5. Dans la section de publication, choisis la branche `main` et le dossier racine
6. GitHub générera l'adresse publique de ton portfolio

Exemple d'adresse :

`https://tonpseudo.github.io/portfolio/`
