# Git Sheet - A Cheatsheet for Git and Github 


## Installation

### Installing Git

``
https://git-scm.com/downloads
``

### Checking the version of Git

``
git --version
``

## Configuration

### Configure name

`
git config --global user.name Name
`

### Configure email

`
git config --global user.email Email
`

## Create a repository

### Initialize an empty git repository

`
git init
`

### Download an existing git repository 

`
git clone URL
`

## Staging Files

### List staged, unstaged and  untracked files

`
git status
`

### Stage changes in a file for the next commit

```
git add [filename]
```

### Add all the files in the current folder for the next commit

```
git add .
```

## Branches

### List all local branches

```
git branch
```

### List all local and remote branches

```
git branch -a
```

### Create a new branch

```
git branch [branchname]
```

### Create a new branch and move to it 

```
git checkout -b [branchname]
```

### Move to an existing branch

```
git checkout [branchname]
```

### Rename current branch

```
git branch -m [new_branchname]
```

### Delete a branch

```
git branch -d [branchname]
```

## Logs

### View all commits in the current branch

```
git log
```

### View last *N* commits in the current branch

```
git log -N
```

## Conventions

- In [word], word refers to a string which varies with filename, foldername, branchname etc.

