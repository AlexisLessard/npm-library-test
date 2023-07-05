##Informations importantes à retenir pour démo npm

* Si le dépôt git est spécifié dans la balise `repository`, alors le package sera publié automatiquement dans les packages du repo
* On peut aussi configurer le publishConfig. On peut mettre une section dans package.json, ou mettre l'url 'https://npm.pkg.github.com' dans la propriété `registry-url` de l'action setup-node. 
* Ne pas oublier d'utiliser le GITHUB_TOKEN pour se connecter au registre


##Documentation
https://docs.github.com/en/actions/publishing-packages/publishing-nodejs-packages#publishing-packages-to-github-packages
https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#publishing-a-package
