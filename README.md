# Git-Task-Day2

# This deletes the branch 'test' after making sure all changes are merged.
```bash
git branch -d test
```
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

# Temporarily save your uncommitted changes.
```bash
git stash
```
# Pop the most recent stash and apply those changes to your working directory.
```bash
git stash pop
```

# To get all tags to get a specific tag bash git tag 1.7
``bash git tag``

# Tell me to delete the tag remotely.
```bash
 git push origin --delete v1.17
```

# Tell me to delete the tag locally.
```bash
bash git tag -d v1.17 
```
