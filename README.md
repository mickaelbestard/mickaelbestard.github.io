# Portfolio — Mickael Bestard

Site statique (HTML + CSS, aucune dépendance de build), prévu pour GitHub Pages.

## Arborescence

```
index.html                    Accueil : positionnement, démarche, projets
projets/
  controle-optimal.html       1. Modéliser et piloter (thèse)
  hpc.html                    2. Simuler efficacement (post-doc)
  deep-rom.html               3. Accélérer pour décider (modèles réduits)
  industrialisation.html      Section secondaire (projet MLOps personnel)
assets/
  style.css                   Feuille de style unique (clair et sombre)
  img/                        Figures de résultats, nommées comme la page
cv/cv-mickael-bestard.pdf     CV téléchargeable
templates/README-projet.md    Modèle de README pour chaque dépôt de démo
.nojekyll                     Sert les fichiers tels quels sur GitHub Pages
.gitignore                    Fichiers système et d'éditeur
```

## Remplir le contenu

Chaque élément à compléter est balisé `<span class="todo">[À compléter : …]</span>`
et s'affiche surligné en jaune. Les remarques de vigilance sont en commentaires HTML
en tête de chaque page projet.

Pour lister ce qui reste à faire :

```bash
grep -rn "À compléter" --include=*.html .
```

Le site est prêt quand cette commande ne renvoie plus rien.

## Mettre en ligne

1. Créer un dépôt `mickaelbestard.github.io` (ou n'importe quel nom).
2. Pousser le contenu de ce dossier sur la branche `main`.
3. Settings → Pages → Source : `main`, dossier `/ (root)`.

Prévisualisation locale : `python3 -m http.server` puis http://localhost:8000.

## Droits

Aucune licence : textes, figures et CV © Mickael Bestard, tous droits réservés.
