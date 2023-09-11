# Git-Task-Day2

# Removing a local branch with merge:
# This deletes the branch 'test' after making sure all changes are merged.
```bash
git branch -d test
```
# Removing a local branch without merge:
# Use this command to forcefully delete the 'test' branch without merging.
```bash
git branch -D test
```

# Removing a remote branch:
# This removes the 'test' branch from the remote repository.
```bash
git push origin --delete test
```

## Checking Out Another Branch Without Committing Changes

# Stashing your changes:
# Temporarily save your uncommitted changes.
```bash
git stash
```
# Retrieving Stashed Changes:
# Pop the most recent stash and apply those changes to your working directory.
```bash
git stash pop
```

