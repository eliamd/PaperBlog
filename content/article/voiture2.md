---
title: "Comment un Nokia 3310 Peut Voler une Voiture"
date: 2023-11-15
draft: false
tags: ["Cybersécurité", "Automobile", "Hacking"]
author: ["Eliam", "Article écris en partie par l'IA"]
images:
- https://kentindell.github.io/assets/images/detective-story/device2.jpg
---


# **Une Intrusion dans la Cybersécurité Automobile**

>Source et très bonne vidéo qui parle de l'article :

<iframe width="560" height="315" src="https://www.youtube.com/embed/dkw2iewOjJw?si=Fz_gMW7N28-TMydI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{{< youtube dkw2iewOjJw >}}




Dans cet article, nous plongeons au cœur d'une **affaire de cybersécurité fascinante** dans le domaine automobile, révélant comment un simple téléphone Nokia 3310 pourrait être transformé en un outil de piratage de voitures.

## L'Origine Insoupçonnée du Vol

Tout commence par un acte apparemment banal : des gangs s'amusant à **démonter les phares des voitures** et à déconnecter les câbles. Ce qui semblait être un simple vandalisme a rapidement pris une tournure plus sombre lorsque des voitures ont commencé à disparaître.

### La Découverte de Yan Tabor

Yan Tabor, un expert en cybersécurité automobile, est devenu une victime inattendue de ces vols. Après une enquête minutieuse, il a découvert que les voleurs utilisaient un dispositif caché, par exemple dans une enceinte JBL ou un Nokia 3310, pour interférer avec le système électronique des voitures.

![Image](https://kentindell.github.io/assets/images/detective-story/device2.jpg)


#### Le Protocole CAN au Cœur du Système

Le cœur de cette vulnérabilité repose sur le protocole CAN (Controller Area Network), un système de communication interne crucial dans les véhicules.

```
+-------------+
|  Calculateur|
|     Porte   |
+-------------+
       |
       v
+-------------+    +-------------+
|  Calculateur|<=> | Calculateur  |
|     Moteur  |    |  Éclairage   |
+-------------+    +-------------+
       ^
       |
+-------------+
|   Injecteur |
|     CAN     |
+-------------+
```

Ce diagramme montre comment le dispositif injecté (Injecteur CAN) se connecte au réseau CAN, interférant avec les calculateurs de la porte et du moteur, tout en se branchant via le système d'éclairage.

#### La Méthode d'Attaque

Les voleurs employaient une technique connue sous le nom de "CAN injection" pour envoyer des signaux imitant ceux d'une clé de voiture valide. Ils accédaient au réseau CAN par le phare, puis déployaient un dispositif pour brouiller la communication entre les autres modules, permettant ainsi à leur signal frauduleux de prendre le dessus.

### Les Solutions Proposées

Pour contrer ces attaques, les experts suggèrent deux solutions principales :
1. **Reprogrammer les passerelles CAN** pour améliorer la détection d'anomalies.
2. **Chiffrer les communications** au sein du réseau CAN, bien que cela implique des défis logistiques importants pour les fabricants.

## Conclusion

Cette affaire soulève des questions importantes sur la **sécurité des véhicules modernes** et la nécessité pour l'industrie automobile de renforcer la protection contre de telles vulnérabilités.
