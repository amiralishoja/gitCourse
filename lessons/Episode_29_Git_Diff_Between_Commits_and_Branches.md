# Episode 29: Git Diff Between Commits and Branches

- Compare changes between commits or branches:
  - `git diff <commit-id>..<commit-id>`: Compares two commits.
  - `git diff <branch-name>..<branch-name>`: Compares two branches.
  - Use a space instead of `..` for the same effect.
- Specify a file to compare changes in that file only: `git diff <commit-id>..<commit-id> <filename>`.