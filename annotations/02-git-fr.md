# Annotations pour le Cours 2 : Utilisation de Git

Utilisation de Git
---
Cette leçon présente l'utilisation de Git pour le contrôle de version et la collaboration sur des projets.

Initialisation de git
---
- Initialisez un nouveau dépôt Git en créant un répertoire de projet depuis la ligne de commande.
- Exécutez la commande `git init` pour commencer à suivre les changements dans votre projet.

Configuration de git
---
- Configurez la configuration globale de Git en utilisant des commandes comme `git config --global init.defaultBranch main`.
- Affichez et gérez les configurations Git avec `cat ~/.gitconfig`.

Branche git
---
- Gérez les branches avec Git en utilisant des commandes comme `git branch -m main`.
- Les branches aident à organiser l'historique du projet et les efforts de développement.

Ajout à git
---
- Mettez en scène les modifications pour la validation avec la commande `git add`.
- Par exemple, utilisez `git add pancakes.md` pour préparer les modifications à valider.

Validation git
---
- Validez les modifications avec Git en utilisant la commande `git commit`.
- Les validations sont des instantanés de l'état actuel de votre projet.

Configuration git à nouveau :/
---
- Configurez à nouveau les paramètres de configuration liés à l'utilisateur pour Git, comme `git config --global user.email "barraponto@gmail.com"`.
- Maintenez une cohérence dans l'auteur et l'identification des validations.

Que faisais-je avec git déjà ?
---
- Vérifiez l'état de votre dépôt Git en utilisant `git status`.
- Comprenez quelles modifications sont prêtes à être validées ou nécessitent de l'attention.

Validation git
---
- Validez les modifications en utilisant `git commit`.
- Rencontrez l'éditeur de texte Vim ; quittez Vim après la validation.

Configuration git (dernière fois)
---
- Configurez l'éditeur principal de Git avec la commande `git config --global core.editor "nano"`.
- Spécifiez l'éditeur de texte préféré pour les opérations Git.

Différence git
---
- Observez les modifications apportées aux fichiers avec `git diff`.
- Mettez en scène et validez les modifications après avoir examiné les différences.

Github
---
- Présentez Github, une plateforme basée sur le web pour l'hébergement et la collaboration de code.
- Créez un dépôt pour le contrôle de version et la collaboration.

Qu'est-ce que SSH ?
---
<div class="max-w-prose mx-auto">
<v-clicks>

- Secure Shell (SSH) est un protocole pour un accès distant sécurisé aux ordinateurs.
- Il prend en charge l'authentification par clé publique, renforçant la sécurité en évitant la transmission de mot de passe.
- SSH chiffre les communications, ce qui le rend précieux pour la gestion à distance, les transferts de données et les proxies.

</v-clicks>
</div>

SSH
---
- Créez une clé SSH pour un accès sécurisé aux dépôts distants.
- Générez des clés avec `ssh-keygen -t ed25519 -C "barraponto@gmail.com"`.

Pousser le dépôt
---
- Liez le dépôt local à un dépôt distant en utilisant `git remote add origin git@github.com:barraponto/usegit-recipes.git`.
- Poussez les validations vers le dépôt distant avec `git push -u origin main`.
