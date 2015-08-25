#Git Cheatsheet
Handy terminal commands for git

##Clone a repo
```
$ git clone <remote> // git clone https://kurt.mcintire@code.company.com/path/path/reponame.git
```

##Navigate to repository
```
$ cd ~/Documents/Repo-name
```

##Which branch am I on?
```
$ git status
```

##Pull / Push
```
$ git pull
$ git push
```

##Commit
```
$ git status
$ git add -- all
$ git commit
$ git commit -m "message about commit"
```

##Sample branch formatting:
```
<branch> = kdm/tabBar-profile-updates
<branch> = 2016.2
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

##Delete a branch
```
$ git push origin —delete <branch>
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
