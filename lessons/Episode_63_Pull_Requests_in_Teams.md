# Episode 63: Pull Requests in Teams

- A **pull request (PR)** allows team members to submit code for review before merging into the main branch.
- Steps:
  - Create a new branch for your changes.
  - Commit and push the branch: `git push -u origin <branch-name>` or `git push --set-upstream origin <branch-name>`.
  - Create a PR in the GitHub repository’s pull request section, selecting the branch and adding a description.
  - After approval, the PR is merged into the main branch.
- Delete the branch after merging:
  - Locally: `git branch -d <branch-name>`
  - Remotely: `git push origin --delete <branch-name>`