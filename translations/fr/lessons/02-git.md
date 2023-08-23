---
theme: default
title: Utiliser git
info: |
  Utiliser Git - Leçon 2 : Utiliser git
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 02-utiliser-git.pdf
---

# Utiliser git

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---

## layout: intro

# git init

- créez votre répertoire de projet **à partir de l'interface en ligne de commande**
- git init

---

## layout: intro

# git config

- git config --global init.defaultBranch main
- cat ~/.gitconfig

---

## layout: intro

# git branch

- git branch -m main
- pas besoin de retenir celle-ci

---

## layout: intro

# git add

- git add pancakes.md

---

## layout: intro

# git commit

- git commit

---

## layout: intro

# git config à nouveau :/

- git config --global user.email "barraponto@gmail.com"
- git config --global user.name "Capi Etheriel"

---

## layout: intro

# git qu'est-ce que je faisais déjà ?

- git status

---

## layout: intro

# git commit

<v-clicks>

- git commit
- omg qu'est-ce que c'est ?
- quitter vim

</v-clicks>

---

## layout: intro

# git config (une dernière fois)

- git config --global core.editor "nano"

---

## layout: intro

# git diff

<v-clicks>

- retournez modifier pancakes.md
- qu'est-ce qui a changé ? `git diff`
- étape : `git add`
- valider : `git commit -m "message"`

</v-clicks>

---

## layout: intro

# Github

- inscrivez-vous (non montré)
- créez un dépôt (repository)
- nous allons utiliser SSH !

---

## layout: statement

# Qu'est-ce que SSH ?

<div class="max-w-prose mx-auto">
<v-clicks>

SSH est un protocole sécurisé pour l'accès à distance aux ordinateurs (serveurs).

Il prend en charge l'**authentification par clé publique** pour éviter d'envoyer des mots de passe sur le réseau.

Il chiffre également fortement toutes les communications qui y passent, ce qui le rend utile pour la gestion à distance, les transferts de données et même les proxys.

</v-clicks>
</div>

---

## layout: intro

# SSH

- ~~qu'est-ce que SSH ?~~
- créez votre clé SSH :
  ssh-keygen -t ed25519 -C "barraponto@gmail.com"
- cat ~/.ssh/id_ed25519.pub
- modifiez vos paramètres Github

<!-- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account -->

---

## layout: intro

# Envoyer le dépôt

- git remote add origin git@github.com:barraponto/usegit-recipes.git
- git push -u origin main
