### Forcing a local update to remote repo

#### Check you're in master branch

`$ git checkout master` // "checks out" to master branch if not already on it

`$ git push -f origin <branch>` // "forces" local state to remote (override)

- If others share the same repo, their revision history will conflict with the new one. If they have local commits after the point of change they will become invalid.
