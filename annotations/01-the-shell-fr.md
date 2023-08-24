Annotations pour la Leçon 1 : Le Shell

Qu'est-ce que le terminal ?
---
Terminal : Le terminal est un programme qui expose le shell en ligne de commande aux utilisateurs, permettant une interaction via des commandes textuelles.

Qu'est-ce qu'un shell ?
---
Shell : Un shell sert d'interface avec l'ordinateur. Les shells graphiques fournissent des icônes et des fenêtres, tandis que les shells en ligne de commande facilitent les opérations d'entrée et de sortie de texte.

Qu'est-ce qu'une commande ?
---
Commande : Les commandes sont des représentations textuelles des demandes de l'utilisateur à l'ordinateur. Par exemple, un e-mail peut être envoyé à l'aide d'une commande telle que `mail --subject="j'ai besoin d'une augmentation" boss@entreprise.com < ./contenu.txt`.

Qu'est-ce qu'un interpréteur ?
---
Interpréteur : Un interpréteur est un programme qui traite et exécute les programmes saisis par l'utilisateur. Il gère la logique, y compris les conditions et les boucles, en en faisant un outil essentiel pour l'exécution de scripts shell.

Qu'est-ce que le PATH ?
---
PATH : Le PATH est une variable d'environnement qui répertorie les répertoires dans lesquels le shell recherche les programmes. Le shell utilise la première correspondance qu'il trouve pour l'exécution du programme.

Qu'est-ce qu'une variable d'environnement ?
---
Variable d'environnement : Les variables d'environnement sont des valeurs nommées accessibles aux commandes du shell. Elles incluent des conventions établies telles que `PWD`, `PATH` et `PS1`, et les utilisateurs peuvent créer leurs propres variables.

Comment puis-je voir les variables d'environnement ?
---
Pour afficher les variables d'environnement actuelles, utilisez la commande `env`.

Comment puis-je configurer ces variables ?
---
Les variables peuvent être configurées à l'aide de fichiers tels que `.bashrc` ou `.zshrc`, permettant la personnalisation de l'environnement du shell.

Quel shell suis-je en train d'exécuter ?
---
Déterminez le shell actif en utilisant la commande `echo $0`.
