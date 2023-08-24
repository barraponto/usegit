---
theme: défaut
titre: Utilisation de Git
info: |
  Utilisation de Git -- Leçon 2 : Utilisation de Git
  Voir https://github.com/barraponto/usegit
transition: déplacer-gauche
dessin:
  persist: faux
exportFilename: 02-utilisation-de-git.pdf
---

# Utilisation de Git

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
notion: intro
---

# git init

- créez votre répertoire de projet **en ligne de commande**
- git init

---
layout: intro
---

# git config

- git config --global init.defaultBranch main
- cat ~/.gitconfig

---
layout: intro
---

# git branch

- git branch -m main
- vous n'avez pas besoin de vous en souvenir

---
layout: intro
---

# git add

- git add pancakes.md

---
layout: intro
---

# git commit

- git commit

---
layout: intro
---

# git config encore :/

- git config --global user.email "barraponto@gmail.com"
- git config --global user.name "Capi Etheriel"

---
layout: intro
---

# git qu'est-ce que je faisais ?

- git status

---
layout: intro
---

# git commit

<v-clicks>

- git commit
- oh mon dieu, qu'est-ce que c'est ?
- quittez vim

</v-clicks>

---
layout: intro
---

# git config (la dernière fois)

- git config --global core.editor "nano"

---
layout: intro
---

# git diff

<v-clicks>

- retournez pour modifier pancakes.md
- qu'est-ce qui a changé ? `git diff`
- étape : `git add`
- commit : `git commit -m "message"`

</v-clicks>

---
layout: intro
---

# Github

- inscrivez-vous (non montré)
- créez un dépôt
- nous allons utiliser SSH !

---
layout: instruction
---

# Qu'est-ce que SSH ?

<div class="max-w-prose mx-auto">
<v-clicks>

SSH est un protocole sécurisé pour l'accès distant aux ordinateurs (serveurs).

Il prend en charge **l'authentification par clé publique** pour éviter l'envoi de mots de passe sur le réseau.

Il chiffre également fortement toutes les communications qui y passent, ce qui le rend utile pour la gestion à distance, les transferts de données et même les proxys.

</v-clicks>
</div>

---
layout: intro
---

# SSH

- ~~qu'est-ce que ssh ?~~
- créez votre clé SSH :
  ssh-keygen -t ed25519 -C "barraponto@gmail.com"
- cat ~/.ssh/id_ed25519.pub
- modifiez vos paramètres Github

<!-- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account -->

---
layout: intro
---

# Poussez le dépôt

- git remote add origin git@github.com:barraponto/usegit-recipes.git
- git push -u origin main
