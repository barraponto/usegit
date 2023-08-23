# Suggestion: Introduce Commitizen for Conventional Commits

## Why Commitizen?

Commitizen is a command line utility that assists developers in writing conventional commits. Conventional commits are a standardized format of writing commit messages, making it easier to manage versions and release notes.

### Benefits

- **Consistency**: All team members will write commit messages in a uniform format.
- **Automated Changelog**: Tools like `semantic-release` can automatically generate a changelog from conventional commits.
- **Easier Debugging**: With structured and predictable commit messages, it's much easier to find out when a bug was introduced.
  
### Practical Example

The tool prompts you to fill out you the biggest changes, breaking changes, affected scope, and so forth, ensuring a uniform commit history. Here's what using Commitizen looks like:

```bash
git cz
```
