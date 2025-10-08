cd advance-git
git merge --abort
git add test2.md
touch .gitignore
echo .> .gitignore
git rm --cached conflict_file.txt
git add .gitignore
git commit -m "Add conflict_file.txt to .gitignore"
git add .gitignore
git commit -m "Add conflict_file.txt to .gitignore"
git tag v1.0
git tag
git tag -d v1.0
git tag
git branch
git branch -d ft/improved-branch-name
git push -u origin main
doskey/history

