![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```


```
4) vercel -v
5) vercel init


6)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel deploy angular
Vercel CLI 21.1.0
? Set up and deploy “~\Desktop\Cours\Vercel\angular”? [Y/n] y
? Which scope do you want to deploy to? arouv
? Link to existing project? [y/N] n
? What’s your project’s name? angularvercel
? In which directory is your code located? ./
Auto-detected Project Settings (Angular):
- Build Command: `npm run build` or `ng build`
- Output Directory: dist
- Development Command: ng serve --port $PORT
? Want to override the settings? [y/N] n
�  Linked to arouv/angularvercel (created .vercel and added it to .gitignore)
�  Inspect: https://vercel.com/arouv/angularvercel/bzvk0vkfp [1s]
✅  Production: https://angularvercel-beryl.vercel.app [copied to clipboard] [1m]
�  Deployed to production. Run `vercel --prod` to overwrite later (https://vercel.link/2F).
�  To change the domain or build command, go to https://vercel.com/arouv/angularvercel/settings

7)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel ls angular

8)C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel logs https://angularvercel-beryl.vercel.app/

9)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel inspect https://angularvercel-beryl.vercel.app/
Vercel inspect permet d'avoir l'arborescence du projet

10)Cela permet d'injecter des valeurs que l'on ne souhaite pas placer directement dans le code source
 et de modifier son comportement en fonction de l'environnement dans lequel il s'exécute.

11)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel env add plain EnvPlain production
Vercel CLI 21.1.0
? What’s the value of EnvPlain? 0

12)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel env list

13)
La commande vercel secrets est utilisée pour gérer les secrets utilisés dans les variables d'environnement 
sous un compte, en fournissant des fonctionnalités pour lister, ajouter, renommer et supprimer des secrets.

15)
C:\Users\Rouvereau Antoine\Desktop\Cours\Vercel>vercel secrets add magicarpe 42

16)il y a 3 environnements: production preview development. Elles definissent a quelle moment ces variables son appliquer.

18)
https://angularvercel-bzvk0vkfp.vercel.app/

```