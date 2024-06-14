# git commands
before creating a new branch (or doing anything), always update your file with changes from github
```console
git pull origin main
```

create a branch locally and switch into it
```console
git checkout -b new_branch
```

push the branch onto github
```console
git push origin new_branch
```

delete a branch on your local system
```console
git branch -d name_of_branch
```

check what branch you're on
```console
git status
```

to see local branches
```console
git branch 
```

to see remote branches
```console
git branch -r
```

to see all branches
```console
git branch -a
```
