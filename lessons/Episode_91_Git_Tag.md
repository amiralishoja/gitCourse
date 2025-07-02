# Episode 91: Git Tag

- Create tags to mark specific commits (e.g., for releases):
  - `git tag <tag-name> <commit-id>`: Creates a tag for a commit.
  - `git tag -d <tag-name>`: Deletes a tag.
  - `git tag -f <tag-name> <new-commit-id>`: Reassigns a tag to a different commit.
- View tags:
  - `git tag` or `git tag -l`: Lists all tags.
  - `git tag -l <pattern>`: Searches for tags (e.g., `git tag -l v2.*`).
- Push tags to remote:
  - `git push <remote-name> <tag-name>`: Pushes a specific tag.
  - `git push <remote-name> --tags`: Pushes all tags.