# Demo

some description!

<<<<<<< HEAD
## clone, add, and pushs
git status: refer the branch and what I modifided
gti add: track the new file
git commit -m "comment title" -m "comment description": the file is still in local
git push: reflact the commit on the github website

## git branch
We put complete modifications on master(main) branch and incomplete ones on feature branch   
gti branch: show which branches are and where you are  
git checkout (branch name):  move to the (brach name)  
git checkout -b (feature brach name): create a new branch and move to there  

## merge 
After add, anc commit on the branch...  
git diff (feature branch name): show the difference between the code on master and (feature branch name) 
git merge:  

alternatively, merge by making a pr...  
git push:  
git push -u origin master  
"-u" means the "--set-upstream"  
go to the github and merge it with comment  

git pull: get the update to local master branch  
git branch -d (feature branch name)  

## conflict
Conflict happens when git doesn't know which part should be overwritten.  
folliwng the instruction on github, modify the code as we want to change  
then do this command:  
git commit -am "comment title"  

## undo
git reset:  undo "git add"  
git reset HEAD~1: undo "git commit"  
-> HEAD means the latest commit and ~1 means going back to one previous step  
git reset (hash):  undo the correspond commit  
gti reset --hard (hash): delete the correspond commit, so the correspond part of code will be deleted  
git log: refer the commit log  

## fork
copy the entire repository under your account  