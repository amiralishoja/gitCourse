# Episode 15: Git Aliases

- Create custom shortcuts for Git commands:
  - `git config --local alias.<shortcut> "<command>"`: Sets an alias for the current project.
  - `git config --global alias.<shortcut> "<command>"`: Sets an alias for all projects.
- View aliases: `git config --global --get-regexp alias`
- Remove an alias: `git config --global --unset alias.<shortcut>`