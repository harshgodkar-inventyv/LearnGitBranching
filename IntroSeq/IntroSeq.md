# Learning Git branching

# Introduction Sequence

## Level - 1

```
git commit
git commit
```
![alt text](image-1.png)
![alt text](image-2.png)

## Level - 2

```
git branch bugFix
git checkout bugFix
```
![alt text](image-3.png)


## Level - 3

```
git branch bugFix
git checkout bugFix
git commit
git checkout main
git commit
git merge bugFix
```

![alt text](image-4.png)


## Level - 4

```
git branch bugFix
git checkout bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main
``

![alt text](image-5.png)