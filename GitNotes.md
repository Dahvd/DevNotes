# Git Notes

### Branching
```
git branch <branch-name>
git branch -d <branch-name>  //delete branch
git checkout -b <branch-name>  //create branch and change to it
```


### Working tree to commit
```
git add .  //adds all files without commiting 
commit all the changes in the directory //commit all changes directory
git restore --staged <file>  //unstage a file
```

### See differences
```
git diff  //to see uncommitted changes
git diff branch1..branch2  //show all file differences
git diff branch1 branch2 ./path/to/file.txt  //see diff between the file of 2 branches
```

### Staching
```
git stash save “<stash-message>  //adds files to stash
git stash save -u  //to add untracked files 
git stash list  //view stashed code
git stash apply  //restore a stash
```

### Utilities
```
git status  //to see currnet branch and staged files
git log //see entire commit history
git log -n #  //see only last # many commits
git log --oneline  //Good overview of commit history
git log --author"<author-username>"  //see commits by authors

```
