---
theme: default
title: Everyday git
info: |
  Use Git -- Lesson 3: Everyday git
  See https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 03-everyday-git.pdf
---

# Everyday git

## with Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
layout: intro
---

# What is a branch?

<v-clicks>

A **branch** is a (linear) history of changes, represented by **commits**.

</v-clicks>

---
layout: intro
---

# What is a commit?

<v-clicks>

A **commit** is a snapshot of your **working tree** at some _meaningful_ moment.

The **tree** is just your files. The **working tree** is the files as they are right now.

To be _meaningful_, you must write down the _meaning_ in the **commit message**.

</v-clicks>

---
layout: intro
---

# Let's do it

<!--

Edit the recipes app.
Commit a new one.
Create a branch to change add categories.
Push the branch.

-->

---
layout: intro
---

# Let's see it

- git-graph
- https://onlywei.github.io/explain-git-with-d3/

---
layout: intro
---

# Concepts

- commits
- branches
- repositories
- remotes
- working trees

---
layout: intro
---

# Commands

- `git switch`
- `git branch`
- `git checkout`
- `git merge`

---
layout: intro
---

# Pull Request

<v-clicks>

A **pull request** or **merge request** is a request to merge commits from a branch into another, usually a **feature branch** into the **mainline branch** (also known as **trunk**).

It is not required, but it allows for **code reviews**.

</v-clicks>

---
layout: intro
---

# Code Review

<v-clicks>

A **code review** is code-related feedback from other developers, ensuring adherence to the project standards and best practices.

It may be followed up by further development (commits) and further reviews too.
</v-clicks>

---
layout: intro
---

# Keeping your local project up to date

- `git stash` may be used to rewind and replay your working tree changes.
- `git fetch` downloads commits and branches, but does not touch your local branches.
- `git pull` will update a local branch to match its **upstream** version.

<!--
    We may see conflicts here (during stash).
    If they show up, branch off from earlier version and apply there.
    Leave conflict management for later, if possible.
-->