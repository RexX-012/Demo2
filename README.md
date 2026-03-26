# Demo 2

## How to connect git to github

1. `git remote add origin <github-repo-url>` - Adds the remote repository.
2. `git push -u origin <branch-name>` - Pushes the changes to the remote repository.

## How to create a new branch

1. `git branch <branch-name>` - Creates a new branch.
2. `git checkout <branch-name>` - Switches to the new branch.
3. `git push -u origin <branch-name>` - Pushes the new branch to the remote repository.

## How to merge a branch

1. `git checkout <branch-name>` - Switches to the branch you want to merge into.
2. `git merge <branch-name>` - Merges the branch into the current branch.
3. `git push` - Pushes the changes to the remote repository.