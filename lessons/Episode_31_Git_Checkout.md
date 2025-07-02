# Episode 31: Git Checkout

- Commands:
  - `git checkout <commit-id>`: Switches to a specific commit to view its state.
  - `git checkout <commit-id> <filename>`: Views a specific file from a commit.
  - `git checkout HEAD~<number>`: Views a commit relative to HEAD (e.g., `HEAD~2` for two commits ago).
  - `git log --all`: Views all commits while in a detached HEAD state.
- Exit detached HEAD state:
  - Switch to a branch: `git switch <branch-name>` or `git switch -`.
  - If viewing a file, run `git checkout <commit-id>` without a filename, then switch to a branch.