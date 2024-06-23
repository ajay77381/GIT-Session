![download](https://github.com/ajay77381/GIT-Session/assets/130822600/b336a295-2621-4757-8766-b3d3e38d4f97)


## What is Versional contral system?

Versional control is a system that record/manages the changes of document /computer program etc over the time. It help us tracking the changes when multiple people work on the same project.

What is GIT?

Git is versional control system that help us to track the changes in the file and computer program . GIT bacially used in source code management in software development  but it can be user for keep records changes of any set of file.




What we did?

We created the directory mkdir / GIT

cd/Git
 We did run git init commond
 

then we find when we creting any file it show untracked stage
 For trackign we need to run commond - git add file name
### Git add - commond push the fiel in staging area

git config --global user.email "you@example.com"

  git config --global user.name "Your Name"

git commit-m - commond will push the fiel in git recorded area


.................

For ignore any file. 

Need to creae 
1>>  .gitignore
2>>   git add .gitignore and git commit .git ignore
3>> put the name of the file inside gitignore



How to show already commited file?

git log --raw

## For push the file on GIT repository

echo "# git" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/ajay77381/GIT-Session.git

git push -u origin main


........................
For switch one branch to another branch.
git checkout branchname
............................

### how to add the branch ?

git branch branchname

### how to push the created branch on remote ?

git push -u origin new createdbranchname

### How to delete branch ?

git branch -d branchname

### Note-Git clone copies all files to the local machine, while git pull only copies the modified files to the local machine. 

### - if you want to check the log of every commit -

git log

git stash

git stash -u

git stash pop

git revert  -- help to revert commit to a previous version .

git revert commitid

.................
For Hide / stash the the untracked file-
git stash -u

How to unstash file?

git stash pop

## Merging branch
Once the devlopers has finished his code /features on his branch code will have to combined with the master branch this can be done two way -
### Git merge

### gitrebase

