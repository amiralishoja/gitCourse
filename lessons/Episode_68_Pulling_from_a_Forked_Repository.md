# Episode 68: Pulling from a Forked Repository

- If the main repository updates after forking:
  - Add a remote to the main repository: `git remote add upstream <main-repo-url>`.
  - Pull updates: `git pull upstream <branch-name>` to sync with the main repository.
- This prevents conflicts when submitting pull requests.