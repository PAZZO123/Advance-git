
git branch
git add feature.txt
git commit -m "Implemented core functionality for new feature"
git switch main
echo .>readme.txt
git commit -m "Updated project readme"
git add readme.txt
git commit -m "Updated project readme"
git checkout main
git merge ft/new-feature
git branch -d ft/new-feature
git log --oneline
git checkout -b ft/new-branch-from-commit i7j8k9l 4904067
git checkout -b ft/new-branch-from-commit 4904067
git add test1.md
git commit -m "WIP: save local changes before branching"
git log --oneline
git checkout -b ft/new-branch-from-commit 4904067
git checkout main
git merge ft/new-branch-from-commit
git log --oneline
git branch
git switch ft/new-branch-from-commit
git checkout -b ft/new-branch-from-commit 4904067
git checkout main
git merge ft/new-branch-from-commit
git log
git switch ft/new-branch-from-commit
git checkout main
git add test1.md
git branch
git status
git add .
git commit -m "some changes"
git checkout main
git merge ft/new-branch-from-commit
Branch Rebasing:
Rebasing is another method to integrate changes from a feature branch. It rewrites your branch history by incorporating its commits on top of the latest commit in the target branch (main in our case).
Challenge: Try rebasing the ft/new-branch-from-commit branch onto the main branch. Remember, rebasing rewrites history, so use it with caution, especially in shared repositories. learn more about rebasing here
git branch
git checkout  ft/new-branch-from-commit
git rebase main
git log
git branch -m ft/new-branch-from-commit ft/improved-branch-name
git log
git log oneline
git log --oneline --graph
git checkout aa89620
git log --oneline
doskey /history
