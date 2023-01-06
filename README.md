# git-cheat-sheet
My git cheat sheet at my fingertips


Push an Existing Local Project to GitHub:

```
$ git init
$ git add -A 
$ git commit -m "commit message"
$ git remote add origin git@github.com:{yourUserName}/{repoName}.git 
$ git push origin main
```
Find out Status:
```
$ git status
```

Push New Changes: 

```
$ git add .
$ git commit -m "commit message"
$ git push origin master 
or
$ git push origin main 
```

Revert the Revert:

```
1- Create a branch from main 

2- To find the commit of the revert [git log -S"search text"]

3- git revert 81d95d1ee98877067d0667ba764029326519f0c7 --no-commit

4- git add, commit and push the changes 

5- Open a new PR with the changes
```

Find Commit by commit message:

```
git log -S "search text"
```
