---
title: Camporder
layout: post
date: 2025-05-01 00:00
image: /assets/images/markdown.jpg
headerImage: false
projects: Camporder
tag:
hidden: false
category: blog
author: vladimir trois
description: Création d'un site de gestion de commandes
---

Après mes différents projets de gestion de commandes pour un camping, je suis en développement d’une solution destinée à tout camping.

Les objectifs évolueront aux fur et à mesures du développement.

Le projet est développé avec Symfony et Nuxt en architecture microservices sous docker.

#### Objectifs

##### Client

- Connexion via un magic link par email.
- Sauvegarde uniquement du Nom Prénom Email Numéro de téléphone.
- Le client peut consulter les articles disponibles de l'établissement.
- Le client peut voir ses anciennes commandes et recommander si possible.
- Il peut recevoir un rappel la veille ou le jour de la commande.
- Il peut effectuer plusieurs commandes sur des jours différents.

##### Admin
- Différents rôles (manager, vendeur, ...)
- En fonction du rôle : gestion des rôles, gestion des articles, des commandes, du stock ou des campings si plusieurs campings sont dans le même groupe.
- Gestion de la plage de vente de l'article.
- Stock automatique des articles.
- Accès aux statistiques des articles. 

### Back end

En cours de réalisation avec Symfony.

### Front end

En cours de réalisation avec Nuxt.