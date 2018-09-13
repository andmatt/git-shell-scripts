# git-shell-scripts
A collection of helpful shell scripts for `git bash`. The general theme is keeping your branch up to date with `origin/master`, and easily tracking and pruning old branches.

### Usage
Clone this repo to your git bash `$PATH` to enable the following custom git commands

```bash
git branches #fetch origin and list all local and remote branches
git cleanup #prune remote branches + corresponding local branches
git fix_commit %1 #change the message of your last commit and unstage all changes
git magic #make your current branch up to date with origin/master 
git new_branch %1 #create a new branch with name `%1`, push it to origin, and sync with origin/master
```
