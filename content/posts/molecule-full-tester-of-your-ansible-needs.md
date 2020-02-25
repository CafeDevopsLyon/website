---
title: "Molecule Full Tester of Your Ansible Needs"
date: 2020-02-21T18:00:00+01:00
speakers:
  - Thibault Lecoq
  - Quentin Le Baron
tags: ["Devops", "Ansible", "test"]
---

<a href="/pdf/Molecule_full_tester_of_your_need.pdf" target="\_blank">Support de présentation</a> 
 
```
le support est sous licence Creative Commons:
- Citer l'auteur.
- Interdiction de tirer un profit commercial de l’œuvre sans autorisation de l'auteur.
- Partage de l’œuvre, avec obligation de rediffuser selon la même licence.
```  
Prérequis : Avoir manipulé Ansible et les rôle Ansible.

Le sujet de cette session sera de présenter dans une première partie l'outil Molecule, pourquoi et comment l'utiliser pour tester du code ansible (rôles, playbooks, modules, filters).

Une démonstration de l'usage de molecule sur un role ansible viendra cloturer cette première partie.

La deuxième partie sera axés sur notre retour d'expérience de comment nous avons intégré molecule dans l'écosystème du projet linky sur lequel nous travaillons aujourd'hui.

Nous verrons pourquoi nous avons choisi d'intégrer molecule, les avantages que cela apporte et en quoi est-ce un investissement rentable. S'en suivra une présentation de l'architecture choisi ainsi qu'une explication détaillé de sa mise en place de A à Z.
Nous terminerons par une démonstration présentant point par point comment mettre en place cette architecure et intégrer dans celle-ci molecule à un rôle ansible.

1er partie Molecule:  
    - Qu'est ce que c'est et pourquoi l'utiliser ?  
    - Comment cela fonctionne et comment l'utiliser  
    - Demonstration sur un role ansible  

2eme partie Intégration continue de Molecule:  
    - Contexte : explication du besoin  
    - Présentation de l'architecture : Jenkins + Gitea + AWS  
    - Explication détaillé du fonctionnement (pipeline, webhook ...)  
    - Demonstration point par point de l'intégration de molecule  

Thibault LECOQ et Quentin LE BARON Intégrateur DevOps sur l'un des projets Linky.