#Git Notes
Handy terminal commands for git


##Delete
```
$ rm <filename>
```

##Merge Conflicts
```
$ git mergetool
```

##Commit
```
$ git status
$ git add -- all
$ git commit
$ git commit -m “message about commit"
```

##Branches Formatting:
```
kdm/tabBar-profile-superfan-views
```

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

##Rebase:
```
$ git status
$ git checkout master
$ git pull
$ git rebase master <branch>
$ git mergetool (optional)
$ git rebase —continue (optional)
$ git rebase —skip (optional)
$ git status (Your branch and 'origin/kdm/edit-profile' have diverged, and have 7 and 8 different commits each, respectively.)
$ git push -f
```

##Delete a Branch
```
$ git push origin —delete kdm/branch-name
```
