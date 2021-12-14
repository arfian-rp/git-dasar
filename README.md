<h1>GIT DASAR</h1>

Written By Arfian

```
git init //init repo
```

```
git add .
```

```
git commit -am "msg" //commit
```

```
git log <opt name file> //show log
```

```
git log --all --decorate --oneline --graph //show visual graph
```

```
git branch //showh all branch
```

```
git branch eka //create new branch eka
```

```
git checkout eka //change branch to eka
```

```
git checkout -b <name branch> //go to branch (if not there will be created)
```

```
<in master branch>
git merge eka //merge eka and master
```

```
git checkout <7 digit first commit hash> //back to commit, change HEAD
```

<h1>GIT REMOTE</h1>

```
git clone <link> //clone repo github ke local (kalau download tidak terhubung secara remote)
```

```
git remote //show remote name
```

```
git remote -v //show all data about remote
```

```
git remote add <remote name> <url repo remote> //add new remote
```

```
git push <remote name> <branch name> //push (send changes to github)
```

```
git fetch <remote name> //see if there are any commit changes on github
```

```
git pull //pull (reverse push)
```

```
//if you use more than 2 remotes, do fetch first to get commit info when using graph command
```

```
git push origin --delete <branch name> //delete branch
```
