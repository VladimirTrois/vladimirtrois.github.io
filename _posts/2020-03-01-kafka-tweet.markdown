---
title: Tweet dashboard
layout: post
date: 2020-03-01 00:00
image: /assets/images/markdown.jpg
headerImage: false
projects: Tweet dashboard
tag:
hidden: false
category: blog
author: vladimir trois
description: Création d'un site de gestion de produits
---

## Description

Projet réalisé avec Kafka et Kafka Streams.

Le but est de récupérer le flux twitter en sélectionnant les tweets qui ont un hashtag spécifique tel que IA,Java,Tech,etc puis d'afficher des métriques en temps réel. Par exemple le nombre de tweets chaque seconde, les thèmes les plus retweet, etc.

- Connexion a twitter [repo](https://github.com/VladimirTrois/kafka-connect-twitter)
- Passage dans un Kafka Streams pour filtrer [repo](https://github.com/VladimirTrois/kafka-twitter-filter)
- Préparation et envoi des données vers un dashboard [repo](https://github.com/VladimirTrois/kstreams-to-dashboard)
- Affichage du dashboard [repo](https://github.com/VladimirTrois/tweet-analytics-dashboard)