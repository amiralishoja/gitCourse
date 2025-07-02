# Episode 90: Git Bisect

- Use `git bisect` to perform a binary search to find the commit that introduced a bug:
  - Start: `git bisect start`
  - Mark a known good commit: `git bisect good <commit-id>`
  - Mark a bad commit: `git bisect bad`
  - Test each commit Git presents, marking it as `git bisect good` or `git bisect bad`.
  - End: `git bisect reset` to return to the original state.