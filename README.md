# Lyes Toumi, portfolio

Portfolio de Lyes Toumi, ingénieur Data & IA résident à Genève (permis B).

En ligne : https://toumilyes.netlify.app

## Contenu

```
index.html        le site complet (HTML, CSS et JS dans un seul fichier)
assets/           photo
cv/               CV PDF en français et en anglais
```

Aucun framework, aucune étape de build : le site s'ouvre tel quel dans un navigateur et se déploie en glissant le dossier sur Netlify.

## Modifier le site

- **Textes** : le français est écrit directement dans le HTML, l'anglais dans l'attribut `data-en` de la même balise. Modifier les deux.
- **Ajouter un projet** : copier un bloc `<article class="proj">` dans la section `#projets`. Ajouter la classe `live` pour un projet déployé (bandeau rouge).
- **Changer les CV** : remplacer les fichiers dans `cv/` en gardant les noms `CV_Lyes_Toumi_General_FR.pdf` et `CV_Lyes_Toumi_General_EN.pdf`.

## Déployer sur Netlify

1. Se connecter sur app.netlify.com et ouvrir le site `toumilyes`.
2. Onglet **Deploys**, glisser le dossier complet dans la zone de dépôt.
