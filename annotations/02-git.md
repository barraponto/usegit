Annotations for Lesson 2: Use Git

Use git
---
This lesson introduces the use of Git for version control and collaboration on projects.

git init
---
- Initialize a new Git repository by creating a project directory from the command line.
- Execute the command `git init` to start tracking changes in your project.

git config
---
- Set global configuration for Git using commands like `git config --global init.defaultBranch main`.
- View and manage Git configurations with `cat ~/.gitconfig`.

git branch
---
- Manage branches with Git using commands like `git branch -m main`.
- Branches help organize project history and development efforts.

git add
---
- Stage changes for commit with the command `git add`.
- For example, use `git add pancakes.md` to prepare changes for commit.

git commit
---
- Commit changes with Git using the command `git commit`.
- Commits are snapshots of your project's current state.

git config again :/
---
- Set user-related configuration settings for Git again, like `git config --global user.email "barraponto@gmail.com"`.
- Maintain consistent authorship and identification for commits.

git what was I doing?
---
- Check the status of your Git repository using `git status`.
- Understand what changes are ready to be committed or need attention.

git commit
---
- Commit changes using `git commit`.
- Encounter the Vim text editor; exit Vim after committing.

git config (last time)
---
- Configure Git's core editor with the command `git config --global core.editor "nano"`.
- Specify the preferred text editor for Git operations.

git diff
---
- Observe changes made to files with `git diff`.
- Stage and commit the changes after reviewing the differences.

Github
---
- Introduce Github, a web-based platform for code hosting and collaboration.
- Create a repository for version control and collaboration purposes.

What is SSH?
---
<div class="max-w-prose mx-auto">
<v-clicks>

- Secure Shell (SSH) is a protocol for secure remote access to computers.
- It supports public key authentication, enhancing security by avoiding password transmission.
- SSH encrypts communication, making it valuable for remote management, data transfers, and proxies.

</v-clicks>
</div>

SSH
---
- Create an SSH key for secure access to remote repositories.
- Generate keys with `ssh-keygen -t ed25519 -C "barraponto@gmail.com"`.

Push the repo
---
- Link the local repository to a remote repository using `git remote add origin git@github.com:barraponto/usegit-recipes.git`.
- Push commits to the remote repository with `git push -u origin main`.
