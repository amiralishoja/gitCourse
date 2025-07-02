# Episode 86: Git Stash

- Save incomplete changes to a stash to work on something else (e.g., fixing a bug):
  - `git stash`: Saves changes with the last commit message.
  - `git stash save "message"`: Saves changes with a custom message.
- View stashes: `git stash list`
- Apply and remove a stash:
  - `git stash pop`: Applies the latest stash and removes it.
  - `git stash pop stash@{<index>}`: Applies a specific stash by index.
- Remove a stash:
  - `git stash drop stash@{<index>}`: Deletes a specific stash.
  - `git stash clear`: Deletes all stashes.