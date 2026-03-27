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

## How to pull a branch

1. `git checkout <branch-name>` - Switches to the branch you want to pull into.
2. `git pull <branch-name>` - Pulls the changes from the remote repository.

## How to delete a branch

1. `git branch -d <branch-name>` - Deletes the local branch.
2. `git push origin --delete <branch-name>` - Deletes the remote branch.

## How to switch between branches

1. `git checkout <branch-name>` - Switches to the branch you want to switch to.
2. `git checkout <branch-name>` - Switches to the branch you want to switch to.

## How to view the status of the files

1. `git status` - Shows the status of the files.
2. `git diff` - Shows the difference between the files.
3. `git diff --staged` - Shows the difference between the staged files.
4. `git diff --cached` - Shows the difference between the cached files.
5. `git diff --staged --cached` - Shows the difference between the staged and cached files.



