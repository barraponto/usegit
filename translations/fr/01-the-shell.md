---
theme: default
title: Utiliser le terminal
info: |
  Utiliser Git - Leçon 1 : Utiliser le terminal
  Voir https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-le-terminal.pdf
---

# Utiliser le Terminal

## avec Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
layout: statement
---

# Qu'est-ce que le terminal ?

<div class="max-w-prose mx-auto">
<v-clicks>

Le terminal est un programme qui expose l'interface en ligne de commande à l'utilisateur final.

</v-clicks>
</div>

---
layout: statement
---

# Qu'est-ce qu'un shell ?

<div class="max-w-prose mx-auto">
<v-clicks>

En général, un shell est une interface vers l'ordinateur.

Un shell graphique permet de cliquer sur des icônes et de voir des sorties graphiques telles que des fenêtres.

Un shell en ligne de commande permet d'entrer du texte (des commandes) et de recevoir en sortie des lignes de texte (la plupart du temps).

</v-clicks>
</div>

---
layout: statement
---

# Qu'est-ce qu'une commande ?

<div class="max-w-prose mx-auto">
<v-clicks>

Une commande est une représentation textuelle de ce qui est demandé à l'ordinateur. Si vous voulez envoyer un courriel à votre patron pour demander une augmentation, déjà rédigé dans un certain fichier, vous pourriez le faire ainsi :

```
mail --subject="j'ai besoin d'une augmentation" boss@company.com < ./contents.txt
```

</v-clicks>
</div>

---
layout: intro
---

# Ouvrez le terminal

---
layout: intro
---

# Configurez le terminal

---
layout: intro
---

# Un programme est-il en cours d'exécution en ce moment ?

---
layout: statement
---

# Qu'est-ce qu'un interpréteur ?

<div class="max-w-prose mx-auto">
<v-clicks>

Un interpréteur est un programme qui prend votre entrée et exécute les programmes nécessaires pour la traiter, _composant_ les programmes si nécessaire.

Il permet également une certaine logique telle que des conditions et des boucles.

Au fait, l'interpréteur est aussi un REPL pour un langage de programmation de collage appelé **script shell**.

</v-clicks>
</div>

---
layout: intro
---

# Comment le shell trouve-t-il les programmes ?

---
layout: statement
---

# Qu'est-ce que le PATH ?

<div class="max-w-prose mx-auto">
<v-clicks>

Le `PATH` est une variable d'environnement standard qui répertorie les répertoires où l'interpréteur doit rechercher les programmes. Le premier répertoire contenant un programme avec ce nom sera utilisé.

</v-clicks>
</div>

---
layout: statement
---

# Qu'est-ce qu'une variable d'environnement ?

<div class="max-w-prose mx-auto">
<v-clicks>

Une variable d'environnement est une valeur avec un nom.

Elles sont disponibles pour vos commandes.

Certaines sont conventionnelles, comme `PWD`, `PATH`, `PS1`.

Vous pouvez également créer vos propres variables.

</v-clicks>
</div>

---
layout: intro
---

# Comment puis-je voir les variables d'environnement ?

R : `env`

---
layout: intro
---

# Comment puis-je configurer ces variables ?

R : `.bashrc` ou `.zshrc` ou cela dépend de votre shell.

---
layout: intro
---

# Quel shell suis-je en train d'utiliser ?

R : `echo $0`

---
---

# Mettons tout en pratique
<br>

Objectif : installer tealdeer 

1. Créer un répertoire `Téléchargements`
2. Accéder à ce répertoire (se déplacer dedans avec cd)
3. Télécharger tealdeer depuis https://github.com/dbrgn/tealdeer/releases
4. Exécuter tealdeer avec `./tealdeer`
   4.1. Modifier les autorisations si nécessaire
5. Placer tealdeer dans le `PATH`
6. Renommer tealdeer (facultatif)
7. Utiliser `tldr` pour tout

