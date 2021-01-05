# Git and Github Cheatsheet

## Installation and Setup

### Installing Git

```
https://git-scm.com/downloads
```

### Checking the version of Git

```
git --version
```

## Configuration

### Configure name

```
git config --global user.name Name
```

### Configure email

```
git config --global user.email Email
```

## Create a repository

### Initialize an empty git repository

```
git init
```

### Download an existing github repository 

```
git clone URL
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



### 21. Pushing everything to the remote repository

```
git push -u origin master
```

## 22. For making a pull request

1. Go to any github repository [for example](https://github.com/mkumail1/PurrfectMatchingHTML-CSS).
2. Tap on folk.
3. Copy the link forked from your copy of the repository.
4. Open terminal and type.
```
git clone <url>
```
5. Add a new branch:
```
git checkout -b <branchname>
```
6. Make changes, then commit.
7. Push your changes.
8. Your repository will automatically show a green button stating **compare & pull request** in the *pull request* section
9. Afterwards use [pull request](https://github.com/mkumail1/PurrfectMatchingHTML-CSS/pulls) to make a request.

## Acknowledgments

