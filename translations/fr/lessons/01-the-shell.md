---
theme: default
title: Utiliser le shell
info: |
  Utiliser Git - Leçon 1 : Utiliser le shell
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-le-shell.pdf
---

# Utiliser le Shell

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---

## layout: statement

# Qu'est-ce que le terminal ?

<div class="max-w-prose mx-auto">
<v-clicks>

Le terminal est un programme qui expose l'interface en ligne de commande à l'utilisateur.

</v-clicks>
</div>

---

## layout: statement

# Qu'est-ce qu'un shell ?

<div class="max-w-prose mx-auto">
<v-clicks>

En général, un shell est une interface vers l'ordinateur.

Un shell graphique permet de cliquer sur des icônes et de voir des sorties graphiques telles que des fenêtres.

Un shell en ligne de commande permettra une entrée de texte (commandes) et une sortie de lignes de texte (la plupart du temps).

</v-clicks>
</div>

---

## layout: statement

# Qu'est-ce qu'une commande ?

<div class="max-w-prose mx-auto">
<v-clicks>

Une commande est une représentation textuelle de ce qui est demandé à l'ordinateur. Si vous souhaitez envoyer à votre patron un e-mail demandant une augmentation, déjà rédigé dans un certain fichier, vous pourriez l'écrire ainsi :

</v-clicks>
</div>

---

## layout: intro

# Ouvrez le terminal

---

## layout: intro

# Configurer le terminal

---

## layout: intro

# Y a-t-il un programme en cours d'exécution en ce moment ?

---

## layout: statement

# Qu'est-ce qu'un interpréteur ?

<div class="max-w-prose mx-auto">
<v-clicks>

Un interpréteur est un programme qui prend votre entrée et exécute les programmes nécessaires pour l'exécuter, _composant_ les programmes si nécessaire.

Il permet également une certaine logique, telle que les conditionnels et les boucles.

Au cas où vous vous poseriez la question, l'interpréteur est également un REPL (Read-Eval-Print Loop) pour un langage de programmation de liaison appelé **shell script**.

</v-clicks>
</div>

---

## layout: intro

# Comment le shell trouve-t-il les programmes ?

---

## layout: statement

# Qu'est-ce que le PATH ?

<div class="max-w-prose mx-auto">
<v-clicks>

Le `PATH` est une variable d'environnement standard répertoriant les répertoires où l'interpréteur doit rechercher les programmes. Le premier répertoire contenant un programme portant ce nom sera utilisé.

</v-clicks>
</div>

---

## layout: statement

# Qu'est-ce qu'une variable d'environnement ?

<div class="max-w-prose mx-auto">
<v-clicks>

Une variable d'environnement est une valeur avec un nom.

Elles sont disponibles pour vos commandes.

Certaines variables conventionnelles sont attendues, telles que `PWD`, `PATH`, `PS1`.

Vous pouvez également créer vos propres variables.

</v-clicks>
</div>

---

## layout: intro

# Comment puis-je voir les variables d'environnement ?

R : `env`

---

## layout: intro

# Comment puis-je configurer ces variables ?

R : `.bashrc` ou `.zshrc` ou selon votre shell.

---

## layout: intro

# Quel shell est en cours d'exécution ?

R : `echo $0`

---

---

# Mettons tout cela en pratique

<br>

Objectif : installer tealdeer

1. Créez un répertoire `Téléchargements`
2. Accédez à ce répertoire (cd dedans)
3. Téléchargez tealdeer à partir de https://github.com/dbrgn/tealdeer/releases
4. Exécutez tealdeer `./tealdeer`
   4.1. Modifiez les autorisations si nécessaire
5. Placez tealdeer dans le `PATH`
6. Renommez tealdeer (facultatif)
7. Utilisez `tldr` pour tout
