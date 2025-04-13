# Complete Guide to GIT

## Commands:

## HEAD : 
- git show HEAD
## Ancestor : 
- git show -s --online b874a5f^
- git show -s --online b874a5f^^
- git show -s --online b874a5f^^^
- git show -s --online b874a5f~1
- git show -s --online b874a5f~2
- git show -s --online b874a5f~3
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
- git checkout new_feature