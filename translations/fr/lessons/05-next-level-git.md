---
theme: default
title: Git au niveau supérieur
info: |
  Utiliser Git - Leçon 5 : Git au niveau supérieur
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 05-git-au-niveau-superieur.pdf
---

# Git au niveau supérieur

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---

## layout: intro

# Théorie des branches

Pourquoi créer des branches en premier lieu ?

---

## layout: intro

# Modèles de branches

- flux de travail basé sur la branche principale (trunk)
- branches de fonctionnalité
- branches de version

---

## layout: intro

# Mettre à jour votre travail

- git merge
- git rebase
- quoi que vous fassiez, gardez vos branches courtes !

---

## layout: intro

# Réécrire l'historique

- git rebase -i

---

## layout: intro

# Assumer vos erreurs

- ~~qui~~ pourquoi a fait ça ?

<!-- Expliquer la logique derrière git blame. -->

---

## layout: intro

# Annuler vos erreurs

- git restore
- git revert

<!--
    tldr git restore
    aussi, que faire si vous voulez annuler partiellement ? git revert -n
 -->

---

## layout: intro

# Voyager dans le temps de vos erreurs

- git amend
- git reset

<!--
    Expliquer les conséquences du voyage dans le temps
    casser quelque chose pour montrer git push -f
    git reset n'est pas dramatique
-->
