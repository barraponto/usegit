Annotations for Lesson 3: Everyday Git

Everyday git
---
This lesson focuses on everyday Git practices and concepts, making version control more manageable and efficient.

What is a branch?
---
A **branch** represents a linear history of changes composed of **commits**.
Branches allow for parallel development without interfering with the main codebase.

What is a commit?
---
A **commit** captures a snapshot of your **working tree** at a specific meaningful point in time.
The **working tree** comprises the current state of your files. A commit's **meaning** should be described in the **commit message**.

Let's do it
---
- Edit the recipes app.
- Create a new commit to capture changes.
- Create a branch to add categories.
- Push the new branch to a remote repository.

Let's see it
---
- Visualize your project's history using tools like `git-graph`.
- Gain insight into Git's internal workings through resources like https://onlywei.github.io/explain-git-with-d3/.

Concepts
---
Understand essential Git concepts, including **commits**, **branches**, **repositories**, **remotes**, and **working trees**.
These concepts form the foundation of Git's version control model.

Commands
---
Learn essential Git commands like `git switch`, `git branch`, `git checkout`, and `git merge`.
These commands facilitate effective branch management and code merging.

Pull Request
---
A **pull request** or **merge request** proposes merging commits from one branch into another, often from a feature branch to the mainline.
While not mandatory, pull requests enable **code reviews**.

Code Review
---
Engage in a **code review** to receive feedback from peers, ensuring adherence to coding standards and best practices.
Code reviews encourage collaborative development and quality control.

Keeping your local project up to date
---
- Use `git stash` to temporarily store changes and replay them later.
- Utilize `git fetch` to download commits and branches without affecting local branches.
- Apply `git pull` to synchronize a local branch with its **upstream** version.
