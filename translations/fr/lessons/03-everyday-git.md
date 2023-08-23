---
theme: default
title: Git au quotidien
info: |
  Utiliser Git - Leçon 3 : Git au quotidien
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 03-git-au-quotidien.pdf
---

# Git au quotidien

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---

## layout: intro

# Qu'est-ce qu'une branche ?

<v-clicks>

Une **branche** est un historique (linéaire) de modifications, représenté par des **commits**.

</v-clicks>

---

## layout: intro

# Qu'est-ce qu'un commit ?

<v-clicks>

Un **commit** est un instantané de votre **arborescence de travail** à un moment _significatif_.

L'**arborescence** est simplement vos fichiers. L'**arborescence de travail** est l'état actuel des fichiers.

Pour être _significatif_, vous devez inscrire le _sens_ dans le **message de commit**.

</v-clicks>

---

## layout: intro

# Passons à l'action

<!--

Modifiez l'application de recettes.
Faites un nouveau commit.
Créez une branche pour ajouter des catégories.
Poussez la branche.

-->

---

## layout: intro

# Voyons cela

- git-graph
- https://onlywei.github.io/explain-git-with-d3/

---

## layout: intro

# Concepts

- commits
- branches
- dépôts (repositories)
- dépôts distants (remotes)
- arborescences de travail (working trees)

---

## layout: intro

# Commandes

- `git switch`
- `git branch`
- `git checkout`
- `git merge`

---

## layout: intro

# Demandes de tirage (Pull Request)

<v-clicks>

Une **demande de tirage** ou **pull request** est une demande de fusion de commits d'une branche vers une autre, généralement d'une **branche de fonctionnalité** vers la **branche principale** (également appelée **trunk**).

Elle n'est pas obligatoire, mais elle permet les **revues de code**.

</v-clicks>

---

## layout: intro

# Revue de code (Code Review)

<v-clicks>

Une **revue de code** est un retour d'information lié au code de la part d'autres développeurs, visant à garantir le respect des normes du projet et des meilleures pratiques.

Elle peut être suivie de développements supplémentaires (commits) et de nouvelles revues également.

</v-clicks>

---

## layout: intro

# Maintenir votre projet local à jour

- `git stash` peut être utilisé pour rembobiner et rejouer les modifications de votre arborescence de travail.
- `git fetch` télécharge les commits et les branches, mais n'affecte pas vos branches locales.
- `git pull` mettra à jour une branche locale pour correspondre à sa version **amont** (upstream).

<!--
    Des conflits peuvent survenir ici (lors du stash).
    S'ils apparaissent, créez une nouvelle branche à partir de la version précédente et appliquez-y les modifications.
    Laissez la gestion des conflits pour plus tard, si possible.
-->
