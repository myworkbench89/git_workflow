# Common Git Commands

## Configuration
- `git config --global user.name "Your Name"`
- `git config --global user.email "you@example.com"`

## Repository Setup
- `git init`
- `git clone <repo-url>`

## Basic Snapshotting
- `git status`
- `git add <file>`
- `git add .`
- `git commit -m "commit message"`
- `git diff`
- `git log`

## Branching & Merging
- `git branch`
- `git branch <branch-name>`
- `git checkout <branch-name>`
- `git checkout -b <branch-name>`
- `git merge <branch-name>`
- `git rebase <branch-name>`

## Remote Repositories
- `git remote -v`
- `git remote add origin <url>`
- `git fetch`
- `git pull`
- `git push`
- `git push -u origin <branch>`

## Undoing Changes
- `git reset`
- `git reset --hard`
- `git checkout -- <file>`
- `git revert <commit>`

## Stashing
- `git stash`
- `git stash pop`
- `git stash list`

## Tagging
- `git tag`
- `git tag <tagname>`
- `git push origin <tagname>`

## Others
- `git rm <file>`
- `git mv <old> <new>`
- `git show`
- `git blame <file>`

> For more, see [Git Documentation](https://git-scm.com/docs)