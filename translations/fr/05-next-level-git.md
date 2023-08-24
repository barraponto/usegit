---
theme: default
title: Next Level git
info: |
  Utilisation de Git - Leçon 5 : Git au Niveau Supérieur
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 05-next-level-git.pdf
---

# Git au Niveau Supérieur

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---

## layout: intro

# Théorie des Branchements

Pourquoi créer des branches en premier lieu ?

---

## layout: intro

# Modèles de Branchements

- flux de travail basé sur la branche principale (trunk)
- branches de fonctionnalités (feature branches)
- branches de publication (release branching)

---

## layout: intro

# Mettre à jour votre travail

- fusionner avec git (git merge)
- réorganiser l'historique avec git (git rebase)
- quoi que vous fassiez, gardez vos branches courtes !

---

## layout: intro

# Réécrire l'historique

- git rebase -i

---

## layout: intro

# Assumer vos erreurs

- ~~qui~~ pourquoi cela s'est produit ?

<!-- Expliquer la raison derrière git blame. -->

---

## layout: intro

# Annuler vos erreurs

- git restore
- git revert

<!--
    TL;DR git restore
    De plus, que faire si vous ne voulez annuler qu'une partie ? git revert -n
 -->

---

## layout: intro

# Voyager dans le temps avec vos erreurs

- git amend
- git reset

<!--
    Expliquer les conséquences du voyage dans le temps
    Casser quelque chose pour montrer git push -f
    git reset n'est pas une grosse affaire
-->
