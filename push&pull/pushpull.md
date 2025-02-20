# Learn Git Branching


# Push & Pull -- Git Remotes!

## Level - 1 : Git Clone Intro

```
git clone
```

![alt text](image.png)

## Level - 2 : Remote Branches

```
git commit
git checkout o/main
git commit
```

![alt text](image-1.png)

## Level - 3 : Git Fettin'

```
git fetch
```
![alt text](image-2.png)

## Level - 4 : Git pullin'

```
git pull
```

![alt text](image-3.png)

## Level - 5 : Faking TeamWork

```
git clone
git fakeTeamwork main 2
git commit
git pull
```

![alt text](image-4.png)


## Level - 6 : Git Pushin'

```
git commit
git commit
git push
```
![alt text](image-5.png)

## Level - 7 : Diverged History

```
git clone
git fakeTeamwork
git commit
git pull --rebase
git push
```
![alt text](image-6.png)


## Level - 8 : Locked Main

```
git checkout -b feature
git branch -f main c1
git push

![alt text](image-7.png)