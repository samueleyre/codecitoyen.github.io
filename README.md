# Site de la Nuit du Code Citoyen

## Installation en local

Une fois que vous avez ruby d'installé sur votre machine :

```bash
bundle Install
```

La config globale, commune à tous les environnements de développement, se trouve dans `_config.yml`. C'est la config qui est utilisée automatiquement par les pages github en production, on y trouve donc aussi les éléments de configuration propres à la production.

Dans `_config.dev.yml` ne figurent **que** les éléments spécifiques au développement local. Ainsi, en lançant la commande ci-dessous, c'est comme lancer le fichier `_config.yml`, mais avec les éléments spécifiques de `_config.dev.yml`.

Lancer le serveur :
```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```


Votre site est visible sur [localhost:4000](localhost:4000)

### Troubleshooting

"Your Ruby version is 2.3.1, but your Gemfile specified 2.3.3:"

	sudo gem update



## Composants

### Thème de base

Toutes les pages types issues du thème de base ([Lavar](http://preview.themeforest.net/item/lavar-portfolio-agency-jekyll-theme/full_screen_preview/15679321?ref=gundoel007)) se trouvent dans le dossier `gabarits`.

### Couleurs

Palette de couleur de référence : [coolors.co](https://coolors.co/ffc857-f9dc5c-3185fc-223951-e84855)

## Resources

- Pour la configuration des liens sur des gh-pages : [Configuring Jekyll for User and Project GitHub Pages](http://downtothewire.io/2015/08/15/configuring-jekyll-for-user-and-project-github-pages/)
