---
title: "Kubernetes, attention aux apprentis sorciers !"
date: 2019-11-07T19:00:00+02:00
speakers:
  - Louis Tournayre
tags: ["DevOps"]
---

<a href="/pdf/Kubernetes_attention_aux_apprentis_magiciens.pdf" target="\_blank">Support de présentation</a>  


La promesse de kube est belle : Déployer et manager vos applications. Mais est-ce réellement si simple ?
Dans cette présentation je vous partagerai 5 points qui me semblent importants avant de basculer sous K8S

L’objectif de cette présentation est de partager les zones à risques de kubernetes et de répondre à ces deux importantes questions :
– Pourquoi et dans quels cas l’utiliser ?
– Qu’est-ce que cela coûte ?

L’on parle beaucoup des avantages, des nombreuses fonctionnalités offertes mais tout n’est pas si beau et si simple.
Par expérience de ce que je peux voir en mission et en tant que formateur K8S je vois de nombreux anti-patterns à kube, anti-patterns qui sont ignorés, soit par effet de mode soit par manque de connaissance.

Les 5 points que j’évoque dans le pitch sont :
– Vous devez comprendre et connaître les différentes typologies d’applications de votre SI, attention au golden hammer !
– Vos applications doivent être “kube friendly”, qu’est-ce que cela signifie et implique ?
– Votre (ou vos) cluster doit être supervisé, comment, par qui/quoi ?
Kube peut/va tomber en panne, comment allez vous gérer ces pannes ?
– Tous les 3 mois une nouvelle release de kube est disponible, vous allez arriver à suivre (sans compter les potentiels CVE qui exigent de mettre à jour le cluster…)?