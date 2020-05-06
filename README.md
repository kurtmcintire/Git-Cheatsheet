# Git Cheatsheet
Handy terminal commands for Git

## Clone a repo
```
$ git clone <remote>
ex. git clone https://kurt.mcintire@code.company.com/path/path/reponame.git
```

## Navigate to repository
```
$ cd ~/Documents/Some-folder/Repo-name
```

## Which branch am I on?
```
$ git status
```

## Pull / Push
```
$ git pull
$ git push
```

## Checkout
```
$ git checkout <branch> // specific branch
$ git checkout <sha1> // specific commit
```

git checkout <sha1>

## Commit
```
$ git status
$ git add -- all
$ git commit
$ git commit -m "message about commit"
```

## Sample branch formatting:
```
<branch> = kdm/tabBar-profile-updates
<branch> = 2016.2
```

## Creating a new branch:
```
$ git checkout master
$ git checkout -b <branch>
$ git push -u origin <branch>
```

## List all branches:
```
$ git branch -a
```

## Discard all local changes
```
$ git checkout -- .
```


## Delete a branch
```
$ git push origin —delete <branch>
```

##Delete a File
```
$ rm <filename>
```

## Merge Conflicts
```
$ git mergetool
```

## Merge without closing branch
```
$ git merge <branch> --ff-only
ex. Switch to master / dev and merge in work from a working branch like 2016.2
```



## Rebase:
```
$ git status
$ git checkout master
$ git pull
$ git rebase master <branch>
$ git mergetool (optional)
$ git rebase —continue (optional)
$ git rebase —skip (optional)
$ git status
$ git push -f
```
