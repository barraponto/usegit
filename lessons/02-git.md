---
theme: default
title: Use git
info: |
  Use Git -- Lesson 2: Use git
  See https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 02-use-git.pdf
---

# Use git

## with Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
layout: intro
---

# git init

- create your project directory **from the command line**
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
- you don't need to remember this one

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

# git config again :/

- git config --global user.email "barraponto@gmail.com"
- git config --global user.name "Capi Etheriel"

---
layout: intro
---

# git what was I doing?

- git status

---
layout: intro
---

# git commit

<v-clicks>

- git commit
- omg what is this?
- exit vim

</v-clicks>

---
layout: intro
---

# git config (last time)

- git config --global core.editor "nano" 

---
layout: intro
---

# git diff

<v-clicks>

- go back to edit pancakes.md
- what changed? `git diff`
- stage: `git add`
- commit: `git commit -m "message"`

</v-clicks>

---
layout: intro
---

# Github

- sign up (not shown)
- create a repository
- we're going to use SSH!

---
layout: statement
---

# What is SSH?

<div class="max-w-prose mx-auto">
<v-clicks>

SSH is a secure protocol for remote access to computers (servers). 

It supports **public key authentication** to avoid sending passwords over the network.

It also heavily encrypts all communication that go through it, making it useful for remote management, data transfers and even proxies.

</v-clicks>
</div>

---
layout: intro
---

# SSH

- ~~what is ssh?~~
- create your ssh key:
  ssh-keygen -t ed25519 -C "barraponto@gmail.com"
- cat ~/.ssh/id_ed25519.pub
- edit your Github settings

<!-- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account -->

---
layout: intro
---

# Push the repo

- git remote add origin git@github.com:barraponto/usegit-recipes.git
- git push -u origin main
---