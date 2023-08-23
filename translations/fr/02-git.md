---
thème : par défaut
titre : Utiliser git
infos : |
  Utiliser Git -- Leçon 2 : Utiliser git
  Voir https://github.com/barraponto/usegit
transition : glisser vers la gauche
dessins:
  persister : faux
exportFilename : 02-use-git.pdf
---

# Utilisez git

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
mise en page : introduction
---

# git init

- créez votre répertoire de projet **à partir de la ligne de commande**
- git init

---
mise en page : introduction
---

# configuration git

- git config --global init.defaultBranch main
- chat ~/.gitconfig

---
mise en page : introduction
---

# branche git

- branche git -m principale
- tu n'as pas besoin de te souvenir de celui-ci

---
mise en page : introduction
---

# git ajouter

- git add pancakes.md

---
mise en page : introduction
---

# git commit

- git commit

---
mise en page : introduction
---

# git config à nouveau :/

- git config --global user.email "barraponto@gmail.com"
- git config --global user.name "Capi Etheriel"

---
mise en page : introduction
---

# git qu'est-ce que je faisais ?

- statut git

---
mise en page : introduction
---

# engagement git

<v-clics>

- git commet
- oh qu'est-ce que c'est ?
- quitter vim

</v-clics>

---
mise en page : introduction
---

# git config (dernière fois)

- git config --global core.editor "nano"

---
mise en page : introduction
---

#diff git

<v-clics>

- revenir pour éditer pancakes.md
- Qu'est ce qui a changé? `git diff`
- étape : `git add`
- commit : `git commit -m "message"`

</v-clics>

---
mise en page : introduction
---

#GitHub

- inscrivez-vous (non affiché)
- créer un référentiel
- nous allons utiliser SSH !

---
mise en page : déclaration
---

# Qu'est-ce que SSH ?

<div class="max-w-prose mx-auto">
<v-clics>

SSH est un protocole sécurisé pour l'accès à distance aux ordinateurs (serveurs).

Il prend en charge l'**authentification par clé publique** pour éviter d'envoyer des mots de passe sur le réseau.

Il crypte également fortement toutes les communications qui le transitent, ce qui le rend utile pour la gestion à distance, les transferts de données et même les proxys.

</v-clics>
</div>

---
mise en page : introduction
---

#SSH

- ~~c'est quoi ssh ?~~
- créez votre clé ssh :
  ssh-keygen -t ed25519 -C "barraponto@gmail.com"
- chat ~/.ssh/id_ed25519.pub
- modifiez vos paramètres Github

<!-- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account -->

---
mise en page : introduction
---

# Pousser le dépôt

- git distant ajouter l'origine git@github.com:barraponto/usegit-recipes.git
- git push -u origine principale
---