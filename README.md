# Module1-C
These are the some practice problems in C programming for beginners.
<br>
Author -- Samiron Lahon

 <!-- To check Git version run this command in terminal or Git Blash -->
 Check Git version :
 git --version

 <!-- To configuring Git run this command in terminal  --> 
 Configuring Git repository :
 git config --global user.name "My Name"
 git config --global user.email "My email"
 git config --list
 
 <!-- clone and status -->

 <!-- Clone : Cloning a repository on our local machine -->
 Cloning repository :
 git clone <-link->
 <!-- Status : Display the state of the code --> 
 Check Git status :
 git status

 <!-- Untracked : New files that git doesn't yet track -->
 <!-- Modified : Changed -->
 <!-- Staged :  File  is ready to be commited -->
 <!-- Unmodified : Unchanged -->

<!-- Add & Commit -->

<!-- add : adds new or changed files  in your working directory to the  Git staging  area -->
Add Command :
git add <-file name->
<!-- commit : it is the record of change -->
Commit Command :
git commit -m "Some message"

<!-- Push Command -->
<!-- push : upload local repo content to remote repo -->
Git Push Command :
git push origin main

<!-- to get into any directory -->
Get into a directory Command :
cd <name of the directory>
<!-- to get out from any directory -->
Get out from directory Command:
cd ..


<!-- make new directory into new folder  -->
Make new Directory command :
mkdir <name of the new directory>

<!-- Initial command -->
<!-- init : used to create a new git repo  -->
Initial Command :
1 :
git init

2:
git remote add origin <-link->
git remote -v   (to verify remote)
git branch      (to check branch)
git branch -M main   (to rename branch)
git push origin main

<!-- Work flow -->
create git repo--clone--changes--add--commit--push
 
 <!-- git branch -->
 Check Git Branch :
  git branch
 Rename Git branch : 
  git branch -M main
 Navigate command : 
  git checkout <-new branch name->
 Create new branch command : 
  git checkout -b <-new branch name->
 Delete branch command : 
  git branch -d <-branch name->


  <!-- Merging code -->

  <!-- way1 -->
 Merging code -
way1 
Compare branches, commit, file  & others :
  git diff <-branch name-> 
 Mering command : 
  git merge <-branch name->

  <!-- way2 -->
  way2 :
  <!-- PR(Pull request) : It lets you tell others about changes you've pushed to a branch in a repository on Github -->
  create a PR   
  PR represents Pull Request      

<!-- Pull Command -->
<!-- used to fetch and download content from a remote repo and immediately update the local repo to match that content. -->
Pull command :
git pull origin main

<!-- Resolving Merge Conflicts -->
<!-- An event that takes place when Git is unable to automatically resolve differences  in code between two commits. -->
  

<!-- Undoing Changes -->
Undoing Chnages commands

case 1 : staged changes 
         
        git reset <-file name->
        git reset

case 2 : commited changes (for one commit)        

        git reset HEAD-1

case 3 : commited changes (for many commits)

        git reset <-commit hash->
        git reset --hard <-commit hash->


<!-- Fork -->
<!-- A fork is a new repository that shares code and visibilty settings with the origina "upstream" repository. -->


<!-- Fork is a rough copy. -->







 
