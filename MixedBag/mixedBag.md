# Learning Git branching

# A Mixed Bag

## Level - 1 : Grabbing Just 1 commit

```
git checkout main
git cherry-pick c4
```
![alt text](image.png)

## Level - 2 : Juggling Commits

```
git rebase -i HEAD~2 (order changed)
git commit --amend
git rebase -i HEAD~2 (order changed)
```

![alt text](image-1.png)

## Level - 3 : Juggling Commits2

```
git checkout main
git cherry-pick c2
git commit --amend
git cherry-pick c3
```

![alt text](image-2.png)


## Level - 4 : Git Tags

```
git tag v0 c1
git tag v1 c2
git checkout c2
```

![alt text](image-3.png)


## Level - 5 : Git Describe

```
git commit
git describe
v1_3_gC7

git describe c5
v1_1_gC5

git describe bugFix
v1_3_gC7
```

![alt text](image-4.png)
