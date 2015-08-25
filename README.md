#Git Cheatsheet
Handy terminal commands for git

##Which Branch Am I On?
```
$ git status
```

##Commit
```
$ git status
$ git add -- all
$ git commit
$ git commit -m "message about commit"
```

##Branches Formatting:
<branch> = kdm/tabBar-profile-superfan-views

##Creating a new branch:
```
$ git checkout master
$ git checkout -b <branch>
$ git push -u origin <branch>
```

##List all branches:
```
$ git branch -a
```

##Delete a Branch
```
$ git push origin —delete kdm/branch-name
```

##Delete a File
```
$ rm <filename>
```

##Merge Conflicts
```
$ git mergetool
```

##Rebase:
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
