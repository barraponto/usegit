# Annotations pour le Cours 5 : Git au Niveau Supérieur

Git au niveau supérieur
---
Dans cette leçon, vous plongerez dans des concepts avancés de l'utilisation de Git, en mettant l'accent sur les stratégies de branches, la gestion des erreurs et la manipulation de l'historique.

Théorie des branches
---
Explorez la question fondamentale de **pourquoi créer des branches** dans les systèmes de contrôle de version comme Git.
Comprenez les avantages de l'isolation du travail, de la collaboration et de la tenue d'un historique propre grâce à des branches bien structurées.

Modèles de branches
---
Apprenez les différents modèles de branches, y compris les **flux de travail basés sur le tronc principal**, les **branches de fonctionnalités** et les **branches de version**.
Chaque modèle a ses avantages et ses cas d'utilisation, vous permettant de choisir l'approche la plus adaptée à votre projet.

Mise à jour de votre travail
---
Découvrez les techniques pour mettre à jour votre travail et intégrer des modifications d'une branche à une autre.
Explorez l'utilisation de `git merge` et `git rebase` pour incorporer des changements tout en maintenant l'organisation des branches et la signification des validations.

Réécriture de l'historique
---
Comprenez le concept de réécriture de l'historique Git en utilisant `git rebase -i`.
Explorez le rébase interactif pour modifier, écraser ou réorganiser des validations, ce qui permet d'obtenir un historique de validations plus propre et mieux organisé.

Assumer vos erreurs
---
Plongez dans le concept d'assumer les erreurs dans votre base de code en comprenant **pourquoi** quelque chose s'est produit plutôt que **qui** en est la cause.
Apprenez à utiliser `git blame` pour retracer les changements et comprendre le contexte derrière chaque ligne de code.

Annuler vos erreurs
---
Apprenez des techniques pour annuler des erreurs en utilisant `git restore` et `git revert`.
Découvrez comment annuler partiellement des changements en utilisant `git revert -n`, permettant une annulation sélective des validations.

Remonter le temps sur vos erreurs
---
Explorez des concepts avancés de manipulation de l'historique, tels que `git amend` et `git reset`.
Comprenez les conséquences de la manipulation de l'historique, y compris l'utilisation potentielle de `git push -f` pour forcer la poussée des changements.
