# proficient-Git-in-one-note

- document [click_here](https://backlog.com/git-tutorial)

### 1 Git flow
![branch](https://github.com/DevOps-Success/proficient-Git-in-one-note/blob/main/images/git-branch.PNG)

### 2 Git branch

- create a branch

```
$ git checkout -b branch_name
$ git add .
$ git commit -m "first commit"
$ git push origin master

```
- Merge branch_name to master
```
$ git checkout master
$ git merge branch_name
Updating 1257027..b2b23c4
Fast-forward
 myfile.txt |    1 +
 1 files changed, 1 insertions(+), 0 deletions(-)
```
 
### 3 Git tag

- create a tag
```
$ git tag v1
```
- or git tag with commit hash
```
$ git tag -a v1.1 9fceb02 -m "Message here"
```

- view tag
```
$ git tag -list
```

- push tag
```
$ git push --tags
```

- check it out
```
$ git checkout v1
```

### 4 Git status and log
- status
```
$ git status
```
- view log
```
$ git log --oneline
```
