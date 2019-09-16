---
title: "Machines Virtuelles : Comment gérer vos images ?"
date: 2019-09-04T19:00:00+02:00
speakers:
  - Mathieu Corbin
description: ""
tags: ["Virtualisation"]
---

<h4>Support pdf: <a href="/pdf/machine_virtuelles.pdf" target="\_blank">Lien</a></h4>  

Bien qu'aujourd'hui beaucoup de gens utilisent le cloud, je trouve que l'on entend assez peu parler de la  
construction des images des machines virtuelles.  
Pourtant, il est possible chez de nombreux cloud provider de déployer et d'utiliser ses propres images.  
Cela présente quelques avantages, comme le fait d'utiliser l'OS de son choix ou d'avoir des images avec des logiciels préinstallés.  
Après avoir présenté ces différents cas d'usage, je parlerais de Packer, un outil d'Hashicorp automatisant la construction d'images.  
Je présenterais son fonctionnement, et son intégration avec les différents cloud provider ou avec des outils comme qemu.  
Je voudrais aussi présenter les différentes problématiques que l'on peut rencontrer lorsque l'on construit une image.

Par exemple, il est possible de construire une image "from scratch" (en faisant une installation complète de l'OS)  
ou bien en partant d'images préfabriquées (comme par exemple les images "Cloud" fournies par Debian, Ubuntu ou Red Hat).  
Les deux techniques, que j'expliquerais, ont chacunes des avantages et des inconvénients.  
Je montrerais aussi comment configurer une image, comment utiliser des outils comme Cloud Init pour pouvoir s'authentifier  
sur la machine virtuelle lors de la phase de construction de l'image,  
et donnerais quelques conseils sur ce qu'il faut vérifier pour fournir une image sécurisée.  
Je présenterais également quelques cas un peu tordus que j'ai dû gérer (comme par exemple construire des images UEFI)  
et comment les résoudre. Je montrerais également comment intégrer le build d'image dans Jenkins.

Dans une seconde partie, je parlerais de comment tester les images. Chez Exoscale,  
nous lançons un certain nombre de tests automatisés lorsqu'une nouvelle image est créée  
(nous testons par exemple si la migration "en live" d'une machine virtuelle  
utilisant cette image d'un hyperviseur à un autre fonctionne correctement).  
J'aimerais présenter dans ce talk comment nous testons nos images  
(un certain nombre de tests que nous réalisons peuvent s'adapter à d'autres contextes).
