# Complete Guide to GIT

## Commands:

## HEAD : 
- To see the changes made in the last commit without using a hash, you can use the git show HEAD command:
**git show HEAD**
- To see the changes made in the last commit without using a hash, you can use the git show HEAD command:
**git show HEAD**
## Ancestor : 
- To see the changes made in short and in one line for the first prior commit: **git show -s --oneline b874a5f^**
- To see the changes made in short and in one line for the second prior commit: **git show -s --oneline b874a5f^^**
- To see the changes made in short and in one line for the third prior commit: **- git show -s --oneline b874a5f^^^**
- To see the changes made in short and in one line for the first prior commit: **- git show -s --oneline b874a5f~1**
- To see the changes made in short and in one line for the second prior commit: **- git show -s --oneline b874a5f~2**
- To see the changes made in short and in one line for the third prior commit: **- git show -s --oneline b874a5f~3**
- To see the changes made in short and in one line for the first prior commit: **git show -s --oneline b874a5f^**
- To see the changes made in short and in one line for the second prior commit: **git show -s --oneline b874a5f^^**
- To see the changes made in short and in one line for the third prior commit: **- git show -s --oneline b874a5f^^^**
- To see the changes made in short and in one line for the first prior commit: **- git show -s --oneline b874a5f~1**
- To see the changes made in short and in one line for the second prior commit: **- git show -s --oneline b874a5f~2**
- To see the changes made in short and in one line for the third prior commit: **- git show -s --oneline b874a5f~3**
## Filter: 
- git log index.js
- git log assets/
- git log -n 2 --oneline
- git log -n 3 --oneline
- git log <SHA>..<SHA> --oneline
- git log HEAD~2..HEAD --oneline
- git log --since=2025-04-13
- git log --until="3 days ago"
- git log --until="today"
- git log --after=2.weeks --before=3.days
- git log --after=2.weeks
- git log --author="Anoop Rajasekhara Warrier <anooprvarrier@zoho.com>"
- git log --grep="initial"
- git log -E --grep="ba.+c"
- git log --author="Anoop Rajasekhara Warrier <anooprvarrier@zoho.com>" -n 1 --oneline index.js
## Formatting:
- git log --format=oneline
- git log --oneline
- git log --format=short
- git log --format=medium
- git log --format=full
- git log --format=fuller
- git log --format=email
- git log --format=raw
- git log -p
- git log --stat
- git log --graph
- git log --graph --all --oneline --decorate
## Branch:
- git branch
- git branch new_feature
- git switch new_feature
- git switch --create new_feature or - git switch -c new_feature
- git switch -f new_feature
- git diff main..new_feature
- git diff new_feature..main
- git branch -m new_feature renamed_new_branch
- git branch -m renamed_new_branch
- git branch -d new_feature
- git branch -D new_feature
- git branch -d new_feature --force
## Merging:
- Merging changes from a another branch(new_branch) to the current branch(main) in local (command to be executed from the local branch to which we have to merge the changes): **git merge new_branch**
- To list the branches which is not merged to current branch(main) in local: **git branch --no-merged**
- To list the branches which is merged to current branch(main) in local: **git branch --merged**