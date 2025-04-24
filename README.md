# Le Resto : Intégration HTML, CSS et Sass

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Ce projet est une page web responsive conçue pour présenter un restaurant de manière attrayante. Il a été développé dans le cadre du tutoriel en ligne "Le Resto" du site FromScratch, mettant en œuvre une intégration soignée de HTML, CSS et Sass.

## Structure du projet

Le projet est organisé de la manière suivante :

* **HTML :** Contient la structure de base de la page web, en utilisant une sémantique HTML5 pour une meilleure accessibilité et référencement.
* **CSS :** Regroupe les feuilles de style générales, la mise en page et la définition de la typographie.
* **Sass :** Utilise le préprocesseur Sass pour une gestion de style plus efficace et organisée, notamment grâce à :
    * **Variables :** Centralisation des couleurs, des polices, des tailles et autres valeurs réutilisables.
    * **Mixins :** Création de blocs de déclarations CSS réutilisables pour éviter la duplication de code.
    * **Nesting :** Imbrication des sélecteurs CSS pour une structure plus claire et une meilleure maintenabilité.

## Fonctionnalités clés

Ce projet met en œuvre plusieurs fonctionnalités techniques pour une expérience utilisateur optimale :

* **Mise en page responsive :** Utilisation de techniques de design responsive (probablement Flexbox et/ou Grid CSS) pour une adaptation parfaite de la page sur différents écrans (ordinateurs, tablettes, mobiles).
* **Animations CSS :** Intégration d'animations subtiles en CSS pour améliorer l'interactivité et l'engagement de l'utilisateur.
* **[Ajoutez ici d'autres fonctionnalités techniques spécifiques que vous avez implémentées, par exemple :]**
    * **Formulaire de contact stylisé.**
    * **Galerie d'images avec effet de survol.**
    * **Navigation fluide avec des transitions douces.**

## Comment utiliser

Pour visualiser ce projet, suivez ces étapes :

1.  Clonez ce dépôt GitHub sur votre machine locale :
    ```bash
    git clone [https://github.com/jeanphilipp/projet-resto/](https://github.com/jeanphilipp/projet-resto/)
    ```
2.  Ouvrez le fichier `index.html` dans votre navigateur web.

Si vous souhaitez modifier ou compiler les fichiers Sass :

1.  Assurez-vous d'avoir Node.js et npm (ou yarn) installés sur votre machine.
2.  Naviguez jusqu'au répertoire du projet dans votre terminal.
3.  Installez les dépendances (si un fichier `package.json` est présent) :
    ```bash
    npm install
    # ou
    yarn install
    ```
4.  Si vous avez configuré un script de compilation Sass (par exemple dans `package.json`), exécutez-le :
    ```bash
    npm run sass:watch # Exemple de commande, peut varier
    # ou
    yarn sass:watch # Exemple de commande, peut varier
    ```
    Cela surveillera les changements dans vos fichiers `.scss` et les compilera automatiquement en `.css`.

## Crédits

Ce projet a été réalisé dans le cadre du tutoriel "Le Resto" disponible sur [FromScratch](https://fromscratch.podia.com/).

## Licence

Ce projet est sous licence [MIT](https://opensource.org/licenses/MIT). Vous êtes libre de le modifier et de le distribuer selon les termes de cette licence.
