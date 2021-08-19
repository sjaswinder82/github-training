# Github Training

Check status of the different files
```
git status
```

Add files to git to commit changes
```
git add <filepath>
git add --all
```

commit your changes 
```
git commit -m "message"
```
if commiting first time you need to add theusername and email in config
```
git config user.name "<name>"
git config user.email "<name>"
```

To check the username and email in config
```
git config user.name 
git config user.email
```

push your changes to Github
```
git push -u origin <branch>
```

Checkout to existing branch
```
git checkout <branch>
```

Checkout to a new branch
```
git checkout -b <new_branch_name>
```

list branch on local
```
git branch <branch>
```

pull new code in a branch from origin 
```
git pull origin <branch>
```

reset all changes from previous commit
```
git reset --hard
```


check differenc from the previoud commit
```
git diff
```

delete branch from local
```
git branch -D <branch>
```