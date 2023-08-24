# Git Command: `git archive`

## Why Use This Command:
The `git archive` command allows you to create a compressed archive of a specified Git tree (usually a branch or a specific commit) without the Git-specific metadata. This is useful when you want to share your codebase with others who do not need the version control history, such as when distributing a snapshot of your project for deployment or sharing source code without exposing the full history.

### Benefits:
- **Reduced Size**: The generated archive contains only the source files and directories, leading to smaller file sizes compared to cloning the entire repository.
- **Security**: Sharing archives without Git metadata reduces the risk of exposing sensitive information present in the commit history.
- **Ease of Sharing**: Provides a simple way to distribute code to collaborators, clients, or for deployment, without exposing internal repository details.

### Practical Example:
Let's say you want to share a specific release of your project's source code with a third party. Using `git archive`, you can create a zip archive of a particular commit or branch, excluding Git-specific files.

```bash
git archive --format=zip --output=my_project_v1.0.zip <source-branch>
```
