---
title: Kasa
publishDate: 2020-03-02 00:00:00
img: /assets/stock-1.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Développez une application web de location immobilière avec React et React Router.
tags:
  - Vscode
  - Git 
  - Github
  - Javascript
  - CSS 
  - React
  - React Router
---

### Scénario

Kasa est une agence de location d'appartements entre particuliers depuis près de 10 ans maintenant. Avec plus de 500 annonces postées chaque jour, Kasa fait partie des leaders de la location d'appartements entre particuliers en France. Le site de Kasa a été codé il y a maintenant plus de 10 ans en ASP.NET avec un code legacy important. Il souhaite refaire entièrement le site avec un nouveau code et un nouveau design.

### Ma mission

Démarrer le projet React et développer l'ensemble de l'application, les composants React, les routes React Routeur, en suivant les maquettes Figma desktops et responsives.

### Fonctionnalités

- Pour le défilement des photos dans la galerie: 
     
    - Si l'utilisateur se trouve à la première image et qu'il clique sur "l'image précédente", la galerie affiche la dernière image.
    
    - Inversement, quand l'image affichée est la dernière de la galerie, si l'utilisateur clique sur "l'image suivante", la galerie affiche la première image.

    - S'il n'y a qu'une seule image, les boutons "suivant" et "précédent" ainsi que la numérisation n'apparaissent pas.

- La galerie doit toujours rester de la même hauteur, celle indiquée sur la maquette Figma. Les images seront donc coupées et cadre de l'image.

- Collapse : Par défaut, les Collapses sont fermés à l'initialisation de la page.

- Si le Collapse est ouvert, le clic de l'utilisteur permet de le fermer: 
     
   - Inversement, si le Collapse est fermé, un clic permet de l'ouvrir. 

### Contraintes techniques

Général:

- Le code ne doit pas produire d'erreur ou de warning dans la console.

Côté React:

- Découpage en composants modulaires et réutillisables.
- Un composant par fichier.
- Structure logique des différents fichiers.
- Utilisation des props entre les composants.
- Utilisation du state dans les comopsants quand c'est nécessaire.
- Gestion des événements.
- Utiliser les listes autant que possible.

Côté Routes:

- Les paramètres des routes sont gérés par React Router dans l'URL pour récupérer les informations de chaque logement.
- Il existe une page par route.
- La page 404 est renvoyée pour chaque route inexistante, ou si une valeur présente dans l'URL ne fait pas partie des données renseignées.
- La logique du routeur est réunie dans un seul fichier. 


 <a href="https://manu870419.github.io/kasa/">Lien du site</a>