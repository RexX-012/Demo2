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



## How to view the log of the files

1. `git log` - Shows the log of the files.
2. `git log --oneline` - Shows the log of the files in a single line.
3. `git log --graph` - Shows the log of the files in a graph.
4. `git log --graph --oneline --decorate --all` - Shows the log of the files in a graph in a single line.
5. `git log --graph --oneline --decorate --all --color` - Shows the log of the files in a graph in a single line with color.
6. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s"` - Shows the log of the files in a graph in a single line with color and pretty format.
7. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>"` - Shows the log of the files in a graph in a single line with color and pretty format and author name.
8. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>"` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date.
9. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>"` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date.
10. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>" --grep="<pattern>"` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date and grep pattern.
11. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>" --grep="<pattern>" --branch="<branch-name>"` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date and grep pattern and branch name.
12. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>" --grep="<pattern>" --branch="<branch-name>" --merges` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date and grep pattern and branch name and merges.
13. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>" --grep="<pattern>" --branch="<branch-name>" --no-merges` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date and grep pattern and branch name and no merges.
14. `git log --graph --oneline --decorate --all --color --pretty=format:"%h - %an, %ar : %s" --author="<author-name>" --since="<date>" --until="<date>" --grep="<pattern>" --branch="<branch-name>" --no-merges --no-walk` - Shows the log of the files in a graph in a single line with color and pretty format and author name and since date and until date and grep pattern and branch name and no merges and no walk.
