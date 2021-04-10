# proficient-Git-in-one-note


### 1 Git flow
![branch](https://github.com/DevOps-Success/proficient-Git-in-one-note/blob/main/images/git-branch.PNG)

### 2 Git branch

- create a branch

```
git checkout -b branch_name
git add .
git commit -m "first commit"
git push origin master

```

### 3 Git tag

- create a tag
```
git tag v1
```
- or git tag with commit hash
```
git tag -a v1.1 9fceb02 -m "Message here"
```

- view tag
```
git tag -list
```

- push tag
```
git push --tags
```

- check it out
```
git checkout v1
```
