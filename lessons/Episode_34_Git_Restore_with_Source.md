# Episode 34: Git Restore with Source

- Restore a file to a specific commit:
  - `git restore --source=<commit-id> <filename>`: Restores a file to the state in the specified commit.
  - Use `HEAD~<number>` to restore to a commit relative to HEAD (e.g., `HEAD~2`).