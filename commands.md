```
git init
git add .
<<<<<<< Updated upstream
git commit -m "Initial commit"
git stash save "Stash initiated"
git stash list
git stash apply
```
=======
git commit m "Initial Commit"
git add .
git stash save "Stash initiated"
git stash list
git stash apply
git stash apply stash@{0}
git stash drop stash@{0}

```

### Git apply vs pop
>>>>>>> Stashed changes
