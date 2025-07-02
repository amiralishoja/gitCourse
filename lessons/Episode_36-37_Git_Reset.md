# Episode 36-37: Git Reset

- **Warning**: `git reset` is a destructive command.
- Commands:
  - `git reset --soft <commit-id>`: Moves changes from the repository to the staging area.
  - `git reset --mixed <commit-id>`: Moves changes from the repository to the working directory (default behavior).
  - `git reset <commit-id>`: Equivalent to `git reset --mixed <commit-id>`.