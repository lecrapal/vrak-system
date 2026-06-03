# Audit des règles

Cette page liste les points à clarifier avant une publication publique des règles. Elle sépare les vrais manques des choix de design assumables.

## Priorité haute

### Progression de classe incomplète

Les pages de classe ne détaillent actuellement que le niveau 1, alors que [Montée de Niveau](06%20-%20Montée%20de%20Niveau.md) indique qu'un personnage débloque une capacité de classe à chaque niveau.

À trancher :

- écrire les capacités de niveau 2 à 5 pour chaque classe ;
- ou modifier la montée de niveau pour dire que les capacités de classe ne sont pas systématiques.

### Dé de vie vs PV fixes

Les classes indiquent un **dé de vie** (`d10`, `d8`, `d6`), mais la création et la progression utilisent des PV fixes. Le terme peut donner l'impression qu'on lance un dé à la création ou à la montée de niveau.

Option simple : remplacer "Dé de vie" par "Profil de PV" ou "Base de PV", sauf si le dé doit vraiment servir mécaniquement.

### Sauvegardes à formaliser

Les sauvegardes apparaissent dans plusieurs règles : effets de zone, fuite, renversement, concentration. Il manque une règle centrale qui dit clairement :

- quand on demande une sauvegarde ;
- quelle stat utiliser ;
- comment fixer la DC ;
- ce qui se passe en cas d'égalité.

### États et conditions

Certaines conditions sont utilisées sans section dédiée : à terre, inconscient, mourant, poison, concentration, fatigue, désarmé. La Fatigue et Mourant sont bien décrits, mais les autres gagneraient à être regroupés.

## Priorité moyenne

### Critiques : règle générale et règle de combat

[Règles de Base](01%20-%20Règles%20de%20Base.md) décrit les 20 naturels comme des succès critiques narratifs. [Combat](04%20-%20Combat.md) précise que le 20 naturel maximise les dégâts et ajoute un effet bonus.

Ce n'est pas contradictoire, mais il faut probablement ajouter une phrase : en combat, la règle spécifique du combat remplace la règle générale.

### Avantage et Désavantage simultanés

La règle explique Avantage et Désavantage séparément, mais pas ce qui arrive si les deux s'appliquent au même jet.

Option classique : ils s'annulent.

### Mise hors d'état de nuire

Le [Scénario de Combat](09%20-%20Scénario%20de%20Combat.md) introduit la possibilité de ne pas tuer une créature en l'annonçant avant l'attaque. Cette règle devrait être ajoutée dans [Combat](04%20-%20Combat.md).

### Poison de l'Ombre

L'[Ombre](Classes/Ombre.md) commence avec 5 doses de poison qui ajoutent +1d4 dégâts, mais il manque :

- la durée d'une dose ;
- l'action nécessaire pour empoisonner une arme ;
- ce qui arrive sur un raté ;
- la possibilité ou non d'acheter ou fabriquer d'autres doses.

### Économie et équipement

Les armes et armures sont listées, mais il n'y a pas encore de prix, rareté ou règle d'achat. Ce n'est pas bloquant si la campagne reste très MJ, mais pour publication GitHub une petite page d'équipement aiderait.

### Domaines du Vestige

Le Vestige choisit un Domaine, avec quelques exemples. Il manque une procédure courte pour aider un joueur à créer un Domaine équilibré.

Exemple de cadrage utile :

- ce que le Domaine peut faire facilement ;
- ce qu'il peut faire avec effort ;
- ce qu'il ne peut jamais faire.

## Priorité basse

### Lexique

Un lexique court rendrait les règles plus publiables : PV, PM, DEF, DC, FOR, AGI, ESP, PRÉ, Avantage, Désavantage, Moral, CD.

### Page joueur et page MJ

Le dossier mélange règles joueur, règles MJ et outils. C'est utilisable, mais une publication GitHub gagnerait à marquer clairement :

- lecture minimale pour joueur ;
- lecture complète pour MJ ;
- outils et documents de calibration.

### Races volontairement non mécaniques

Les races n'ont aucun bonus mécanique. C'est clair dans [Création de Personnage](02%20-%20Création%20de%20Personnage.md), mais il peut être utile d'ajouter une phrase de design : les races servent à la fiction, pas à optimiser les statistiques.

## Liens de publication

Déjà fait :

- ajout d'un [index GitHub](README.md) ;
- ajout d'un hub [Classes](03%20-%20Classes.md) ;
- création d'une page par classe dans [Classes](Classes/) ;
- ajout d'illustrations de classe dans [assets/classes](assets/classes/) ;
- remplacement de plusieurs liens Obsidian par des liens Markdown compatibles GitHub.

À poursuivre :

- transformer les derniers liens internes implicites en liens Markdown ;
- ajouter une page "Lecture rapide joueur" ;
- choisir si les outils MJ doivent rester dans le même dossier que les règles publiées.
