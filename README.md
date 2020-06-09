# GIT

## Branching / Version Control

### Most importang Git commands:

* git config
* git init
* git clone
* git add
* git commit
* git diff
* git reset
* git status
* git rm
* git log
* git show
* git tag
* git branch
* git checkout
* git merge
* git remote
* git push
* git pull
* git stash

### My Branches in this Example

* master
* dev
* features
* bugfix



### Some Changes in Code

#### Pull from Git

```git
git pull
```

<img src="/image/gitPull.JPG"
     alt="git pull in console"
     style="float: left; margin-right: 10px;" />  


#### Add Changes / Commit / Push

```git
git add -A
```

<img src="/image/gitAdd_A.JPG"
     alt="git add in console"
     style="float: left; margin-right: 10px;" />


```git
git commit -m "Add message"
```      
<img src="/image/gitCommit_m.JPG"
     alt="git commit in console"
     style="float: left; margin-right: 10px;" />    


 ```git
git push
```    
<img src="/image/gitPush.JPG"
     alt="git push in console"
     style="float: left; margin-right: 10px;" />
     
    
#### Show all / Change Branch 

```git
git branch -a
```  
<img src="/image/gitBranch_a.JPG"
     alt="git branch in console"
     style="float: left; margin-right: 10px;" />
 
 
```git
git checkout branchname
``` 
 <img src="/image/gitCheckoutBugfix.JPG"
     alt="git checkout in console"
     style="float: left; margin-right: 10px;" />


#### Merge / Rebase Branch

```git
git merge branchname
``` 
     
 <img src="/image/gitMergeBugfix.JPG"
     alt="git merge in console"
     style="float: left; margin-right: 10px;" />
 
 <img src="/image/gitMergeDev.JPG"
     alt="git merge in console"
     style="float: left; margin-right: 10px;" />
     
<img src="/image/gitMergeMaster.JPG"
     alt="git merge in console"
     style="float: left; margin-right: 10px;" />


```git
git rebase branchname
``` 

<img src="/image/gitRebaseBugfix.JPG"
     alt="git rebase in console"
     style="float: left; margin-right: 10px;" />


#### Status

```git
git status
``` 

<img src="/image/gitStatus.JPG"
     alt="git status in console"
     style="float: left; margin-right: 10px;" />

<img src="/image/gitStatusAfterMerge.JPG"
     alt="git status in console"
     style="float: left; margin-right: 10px;" />



#### Log

```git
git log
``` 
<img src="/image/gitLog.JPG"
     alt="git log in console"
     style="float: left; margin-right: 10px;" />    


#### Cherry-pick


```git
git cherry-pick hash_of_commit
``` 

<img src="/image/gitCherryPick.JPG"
     alt="git network graph"
     style="float: left; margin-right: 10px;" />



#### Git Network Graph

<img src="/image/gitNetworkGraph.JPG"
     alt="git network graph"
     style="float: left; margin-right: 10px;" />

