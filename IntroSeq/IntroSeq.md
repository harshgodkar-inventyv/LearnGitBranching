# Learning Git branching

# Introduction Sequence

## Level - 1 : Intoduction to Git Commits

```
git commit
git commit
```
![alt text](image-1.png)
![alt text](image-2.png)

## Level - 2 : Branching in Git

```
git branch bugFix
git checkout bugFix
```
![alt text](image-3.png)


## Level - 3 : Merging in Git

```
git checkout -b bugFix
git commit
git checkout main
git commit
git merge bugFix
```

![alt text](image-4.png)


## Level - 4 : Rebase Introduction

```
git checkout -b bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main
```

![alt text](image-5.png)