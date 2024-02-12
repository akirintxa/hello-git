git config --global user.name "username"

git config --global user.email "email@email.com"

git init

git add filename

git commit - m "Commit description"

git status

git log

git log --graph

git log --graph --pretty=oneline

git log --graph --decorate --all --oneline

git checkout filename #volver a la versión anterior de ese archivo

git reset #volver al último estado del último commit

git config --global alias.tree "log --graph --decorate --all --oneline"

git ignore

git reset --hard commitid

git reflog

git tag v1.0

git merge branchname

# Cuando hay conflictos

# 1. Se corrige en el editor

# 2. Se hace git add del archivo

# 3. Se hace git commit -m "Correccion de conflicto"

git stash
