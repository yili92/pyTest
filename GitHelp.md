# Git Help

## create
git clone URL

git init

## local changes
git status

git diff

git add .

git add -p <file>

git commit -a

git commit

git commit --amend

# commit history
git log

git log -p <file>

git blame <file>

# branches & tags
git branch -av

git checkout <branch>

git branch <new-branch>

git checkout --track <remote/branch>

git branch -d <branch>

git tag <tag-name>

# update & publish
git remote -v

git remote show <remote>

git remote add <shortname> <url>

git fetch <remote>

git pull <remote> <branch>

git push <remote> <branch>

git branch -dr <remote/branch>

git push --tags

## merge & rebase
git merge <branch>

git rebase <branch>

git rebase --abort

git rebase --continue

git mergetool

git add <resolved-file>

git rm <resolved-file>

## undo
git git reset --hard HEAD

git checkout HEAD <file>

git revert <commit>

git reset --hard <commit>

git reset <commit>

git reset --keep <commit>
