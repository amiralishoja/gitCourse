# Episode 15: Git Aliases

- Create custom shortcuts for Git commands:
  - `git config --local alias.<shortcut> "<command>"`: Sets an alias for the current project.
  - `git config --global alias.<shortcut> "<command>"`: Sets an alias for all projects.
- View aliases: `git config --global --get-regexp alias`
- Remove an alias: `git config --global --unset alias.<shortcut>`
- git commit -am or git ac ? git commit -am does add your modifyed files in stage but doesn't add new files in your stage so you have to creat a new shortcut for yourself to add everything in your stage and then commit it. it's a trick for you : `git config --global alias.ac '!git add . && git commit -m'`
