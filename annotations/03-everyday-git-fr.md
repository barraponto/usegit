# Annotations pour le Cours 3 : Git au Quotidien

Git au quotidien
---
Cette leçon met l'accent sur les pratiques et les concepts Git quotidiens, rendant le contrôle de version plus gérable et efficace.

Qu'est-ce qu'une branche ?
---
Une **branche** représente un historique linéaire de modifications composé de **commits**.
Les branches permettent un développement parallèle sans interférer avec la base de code principale.

Qu'est-ce qu'un commit ?
---
Un **commit** capture un instantané de votre **arborescence de travail** à un moment précis et significatif.
L'**arborescence de travail** comprend l'état actuel de vos fichiers. La **signification** d'un commit devrait être décrite dans le **message de commit**.

Passons à l'action
---
- Modifiez l'application de recettes.
- Créez un nouveau commit pour capturer les changements.
- Créez une branche pour ajouter des catégories.
- Poussez la nouvelle branche vers un dépôt distant.

Voyons cela
---
- Visualisez l'historique de votre projet à l'aide d'outils comme `git-graph`.
- Gagnez une compréhension des rouages internes de Git grâce à des ressources comme https://onlywei.github.io/explain-git-with-d3/.

Concepts
---
Comprenez les concepts essentiels de Git, notamment les **commits**, les **branches**, les **dépôts**, les **dépôts distants** et les **arborescences de travail**.
Ces concepts constituent la base du modèle de contrôle de version de Git.

Commandes
---
Apprenez les commandes Git essentielles telles que `git switch`, `git branch`, `git checkout` et `git merge`.
Ces commandes facilitent une gestion efficace des branches et la fusion du code.

Demande de tirage (Pull Request)
---
Une **demande de tirage** ou **pull request** propose de fusionner des commits d'une branche dans une autre, souvent d'une branche de fonctionnalité à la branche principale.
Bien que non obligatoires, les demandes de tirage permettent les **revues de code**.

Revue de code (Code Review)
---
Participez à une **revue de code** pour recevoir des commentaires de vos pairs, garantissant le respect des normes de codage et des meilleures pratiques.
Les revues de code encouragent le développement collaboratif et le contrôle de la qualité.

Maintenir à jour votre projet local
---
- Utilisez `git stash` pour stocker temporairement les modifications et les rejouer ultérieurement.
- Utilisez `git fetch` pour télécharger des commits et des branches sans affecter les branches locales.
- Appliquez `git pull` pour synchroniser une branche locale avec sa version **amont**.
