---
title: "Application Mobile YOLO reconnaissance alphabet LSF"
description: "Création d'une application mobile permettant de reconnaître l'alphabet de la Langue des Signes Française via la caméra du téléphone"
dateString: Octobre 2025 - Février 2026
draft: false
tags: ["React Native", "Mobile", "IA", "YOLO", "Expo Go", "Équipe"]
showToc: false
weight: 10
--- 
### 🔗 [GitHub](https://github.com/Celche12/sa-3-01-phase-2)

## Description

Dans le cadre de la SAÉ de ma 3ème année de BUT Informatique au sein de l'IUT de Metz, j'ai dû réaliser, aux côté de Chris VARAGNAT, Robin PAQUET--KREMER et Mei-Yi HO, une application mobile accueillant un modèle de reconnaissance d'images via la galerie ou l'application caméra du téléphone. Nous avons alors choisi d'utiliser YOLO, un modèle reconnu, très utilisé et très documenté, dans notre application codée en React Native, langage lui aussi assez récent et très utilisé, afin de reconnaître les différents signes composant l'alphabet de la Langue des Signes Française (LSF).

Nous lui avons donc fourni un certain nombre de données (photos) dans lesquelles apparaissent lesdits signes, mais aussi certaines avec des signes n'ayant aucun rapport et même des photos sans aucune main, donc sans aucun signe à analyser. Une fois cela fait, il a fallu entraîner le modèle au fil de plusieurs générations, en veillant toutefois à ne pas le surentraîner, afin de le forcer à ne pas se reposer sur les données qu'il possède déjà mais bien à reconnaître le signe sur n'importe quelle image.

Afin de faire dialoguer le modèle avec notre application, nous avons utilisé Expo Go, l'outil le plus pertinent et simple à utiliser dans ce contexte.