# Git Version

```
$ git --version
```

# Git Config

## 1. set user name, email

```
$ git config --global user.name MudOnTire

$ git config --global user.email 895157882@qq.com
```

## 2. get config

```
$ git config user.name

$ git config user.email
```

# Repository

## 1. git init

```
$ git init
```

## 2. git status

```
$ git status
```

## 3. stage file

### single file
```
$ git add index.html 
```

### all changed files
```
$ git add .
```

## 4. unstage file

```
$ git rm --cache index.html
```

## 5. commit

### make commit

```
$ git commit -m "add index and style files"
```

### show history

```
$ git log
```

### show condensed commit

```
$ git log --oneline
```

# Undo Commits

## 1. checkout commit

```
$ git checkout 0e2a5f3
```

## 2. reattach to branch

```
$ git checkout master
```

## 3. revert commit (undo one particular commit)

```
$ git revert eb95c64
```

## 4. reset commits

### soft (retain changes)

```
$ git reset eb95c64
```

### hard (erase all changes)

```
$ git reset eb95c64 --hard
```

# Create Branch

## 1. show branches

```
$ git branch -a
```

## 2. create a branch

```
$ git branch feature-1
```

## 3. switch to a branch

```
$ git checkout feature-1
```

## 4. delete a branch

```
$ git branch -D feature-1
```

## 5. create and then switch to a branch 

```
$ git checkout -b feature-1
```

# Merge Branch

## 1. merge target branch to current branch

```
$ git merge [name_of_target_branch]
```

# Push

## 1. push branch to github

```
$ git push https://github.com/MudOnTire/git-test.git master
```

## 2. give alias to remote repository

```
$ git remote add origin https://github.com/MudOnTire/git-test.git
```

## 3. push local branch to remote with alias

```
$ git push origin [name_of_your_new_branch]
```





