---
title: PIIQUANTE
publishDate: 2020-03-04 00:00:00
img: /assets/stock-3.jpg
img_alt: Sauces piquantes
description: |
  Développez une API sécurisée pour une application d'avis gastronomiques.
tags:
  - Node.js
  - Express.js
  - MongoDB
  - API REST
  - Back-end
---

### Scénario

Nous avons reçu un message sur notre plateforme de freelance nous demandant de l'aide pour un nouveau projet. Les sauces piquantes sont de plus en plus populaires, en grande partie grâce à la série YouTube « Hot Ones » . C’est pourquoi ce nouveau client, la marque de condiments à base de piment Piiquante, veut développer une application web de critique des sauces piquantes appelée « Hot Takes » .

### Ma mission
Développer le Back-end pour construire l'API du site.

### Fonctionnalités

L'entreprise souhaite créer une application web dans laquelle les utilisateurs peuvent ajouter leurs sauces préférées et liker ou disliker les sauces ajoutées par les autres.
  - API Errors
Les erreurs éventuelles doivent être renvoyées telles qu'elles sont produites, sans modification ni ajout. Si nécessaire, utilisez une nouvelle Error().

  - API Routes
Toutes les routes sauce pour les sauces doivent disposer d’une autorisation (le token est envoyé par le front-end avec l'en-tête d’autorisation : « Bearer <token> »).
Avant que l'utilisateur puisse apporter des modifications à la route sauce, le code doit vérifier si l'userId actuel correspond à l'userId de la sauce. Si l'userId ne correspond pas, renvoyer « 403: unauthorized request. » Cela permet de s'assurer que seul le propriétaire de la sauce peut apporter des modifications à celle-ci.

### Contraintes techniques

- Le mot de passe de l'utilisateur doit être haché.
- L'authentification doit être renforcée sur toutes les routes sauce requises.
- Les adresses électroniques dans la base de données sont uniques et un
plugin Mongoose approprié est utilisé pour garantir leur unicité et signaler
les erreurs.
- La sécurité de la base de données MongoDB (à partir d'un service tel que
MongoDB Atlas) ne doit pas empêcher l'application de se lancer sur la
machine d'un utilisateur.
- Un plugin Mongoose doit assurer la remontée des erreurs issues de la base
de données.
- Les versions les plus récentes des logiciels sont utilisées avec des correctifs de sécurité actualisés.
- Le contenu du dossier images ne doit pas être téléchargé sur GitHub.


<a href= ""> Lien du site</a>