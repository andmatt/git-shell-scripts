# git-shell-scripts
A collection of helpful shell scripts for `git bash`. The general theme is keeping your branch up to date with `origin/master`, and easily tracking and pruning old branches.

### OSX Instructions
First `cd` to your desired file location and clone the repo

    git clone https://github.com/andmatt/git-shell-scripts.git

After cloning the repo - add the location to `$PATH` by adding the following line to your `.bash_profile`.

    source ~/.bash_profile

You can use the `echo >>` command or manually open the file with `open -a TextEdit ~/.bash_profile`

Then `cd` to your path and apply `execute` permissions to the files

    chmod 777 *

### Usage

```bash
git branches #fetch origin and list all local and remote branches
git cleanup #prune remote branches + corresponding local branches
git fix_commit %1 #change the message of your last commit and unstage all changes
git magic #make your current branch up to date with origin/master 
git new_branch %1 #create a new branch with name `%1`, push it to origin, and sync with origin/master
git lazy_commit %1 #commit and ignore all pre-commit hooks
```
