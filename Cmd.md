# Exo 1

git clone https://github.com/Areskizb/examgit/
git branch hotfix
git branch dev
git switch dev
git add .
git commit -m "Init"
git push
git branch feature-url
touch Cmd.md
git add .
git commit -m "Init"
git push
git switch hotfix
git rebase main
git switch main
git merge hotfix
git add .
git push
git tag v0.1 38daca3
git tag v0.2 2b7345d
