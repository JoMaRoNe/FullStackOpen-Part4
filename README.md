# FullStackOpen-Part4

## Using branchs in GitHub

Check the current branch:
``` bash
git branch
```

Changing the current branch to the last one:
``` bash
git checkout Part4-Ex4.1
```

Creating a new one and changing:
``` bash
git checkout -b Part4-Ex4.2
```

Uploading to GitHub:
``` bash
git push origin Part4-Ex4.2
```

Once we have finished with the exercise, we have to change again to main branch, update it and merge with the last changes and push the main branch:
``` bash
git checkout main
git pull origin main
git merge Part4-Ex4.2
git push origin main
```
