# Learning Git branching

# Ramping Up

## Level - 1 : Detach HEAD

```
git checkout c4
```

![alt text](image.png)


## Level - 2 : Relative Refs(^)

```
git checkout c3
```

![alt text](image-1.png)


## Level - 3 : Relative Refs2(~)
```
git branch -f main c6
git checkout HEAD~1
git branch -f bugFix HEAD~1
```

![alt text](image-2.png)

## Level - 4 : Reversing Changes in Git

```
git reset HEAD~1
git checkout pushed
git revert HEAD
```
![alt text](image-3.png)