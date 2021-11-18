# Git-Cheatsheet

## Going back to a previous commit
```
git log --oneline (Get commit number of commit you want to go back to)
git revert <number>

```

## Fetching latest changes from master
```
git fetch && git pull origin master
```


## Changing Specific Files to be like how they are on master
```
git checkout origin/master -- <path of file you want to change>
git add .
git commit -m "Your message"
git push
```
