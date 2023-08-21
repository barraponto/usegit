---
theme: default
title: Use the shell
info: |
  Use Git -- Lesson 1: Use the shell
  See https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-the-shell.pdf
---

# Use The Shell

## with Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
layout: statement
---

# What is the terminal?

<div class="max-w-prose mx-auto">
<v-clicks>

The terminal is a program that exposes the command-line shell to the end user.

</v-clicks>
</div>

---
layout: statement
---

# What is a shell?

<div class="max-w-prose mx-auto">
<v-clicks>

Generally speaking, a shell is an interface to the computer.

A graphical shell allows clicking on icons and seeing graphical outputs such as windows.

A command-line shell will allow text input (commands) and output text lines (most of the time).

</v-clicks>
</div>

---
layout: statement
---

# What is a command?

<div class="max-w-prose mx-auto">
<v-clicks>

A command is a textual representation of what is requested from the computer. If you want to send your boss an email asking for raise, already written in a certain file, you could write it like this:

```
mail --subject="i need a raise" boss@company.com < ./contents.txt
```

</v-clicks>
</div>

---
layout: intro
---

# Open up the terminal

---
layout: intro
---

# Configure the terminal

---
layout: intro
---

# Is there a program running right now?

---
layout: statement
---

# What is an interpreter?

<div class="max-w-prose mx-auto">
<v-clicks>

An interpreter is a program that takes your input and runs the programs required to execute it, _composing_ programs if necessary.

It also allows for some logic such as conditionals and loops.

In case you're wondering, the interpreter is also a REPL for a glue programming language called **shell script**.

</v-clicks>
</div>

---
layout: intro
---

# How does the shell find the programs?

---
layout: statement
---

# What is the PATH?

<div class="max-w-prose mx-auto">
<v-clicks>

The `PATH` is a standard _environment variable_ listing directories where the interpret should look for programs. The first one holding a program with that name will be used.

</v-clicks>
</div>

---
layout: statement
---

# What is an environment variable?

<div class="max-w-prose mx-auto">
<v-clicks>

An environment variable is a value with a name.

They are available to your commands.

Some conventional ones are expected, such as `PWD`, `PATH`, `PS1`.

You can create your own variables too.

</v-clicks>
</div>

---
layout: intro
---

# How can I see the environment variables?

A: `env`

---
layout: intro
---

# How can I configure those variables?

A: `.bashrc` or `.zshrc` or depends on your shell.

---
layout: intro
---

# What shell am I running?

A: `echo $0`

---
---

# Let's put it all to use
<br>

Goal: install tealdeer 

1. Create a directory `Downloads`
2. Enter that directory (cd into it)
3. Download tealdeer from https://github.com/dbrgn/tealdeer/releases
4. Run tealdeer `./tealdeer`
  4.1. change permissions if necessary
5. Put tealdeer in the `PATH`
6. Rename tealdeer (optional)
7. `tldr` all the things