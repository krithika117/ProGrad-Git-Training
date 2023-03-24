```
git init
git add .
git commit m "Initial Commit"
git add .
git stash save "Stash initiated"
git stash list
git stash apply
git stash apply stash@{0}
git stash drop stash@{0}
# or
git stash pop
git commit -m "Commit Message"
git push -u origin main
```
