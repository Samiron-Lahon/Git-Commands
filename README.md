# Module1-C
These are the some practice problems in C programming for beginners.
<br>
Author -- Samiron Lahon

 <!-- To check Git version run this command in terminal or Git Blash -->
 git --version

 <!-- To configuring Git run this command in terminal  -->
 git config --global user.name "My Name"
 git config --global user.email "My email"
 git config --list
 
 <!-- clone and status -->

 <!-- Clone : Cloning a repository on our local machine -->
 git clone <-link->
 <!-- Status : Display the state of the code -->
 git status

 <!-- Untracked : New files that git doesn't yet track -->
 <!-- Modified : Changed -->
 <!-- Staged :  File  is ready to be commited -->
 <!-- Unmodified : Unchanged -->

<!-- Add & Commit -->

<!-- add : adds new or changed files  in your working directory to the  Git staging  area -->
git add <-file name->
<!-- commit : it is the record of change -->
git commit -m "Some message"

<!-- Push Command -->
<!-- push : upload local repo content to remote repo -->
git push origin main

<!-- to get into any directory -->
cd <name of the directory>
<!-- to get out from any directory -->
cd ..


<!-- make new directory into new folder  -->
mkdir <name of the new directory>

<!-- Initial command -->
<!-- init : used to create a new git repo  -->
git init
git remote add origin <-link->
git remote -v   (to verify remote)
git branch      (to check branch)
git branch -M main   (to rename branch)
git push origin main

<!-- Work flow -->
create git repo--clone--changes--add--commit--push
 
 <!-- git branch -->
  git branch                               (to check branch)
  git branch -M main                       (to rename branch)
  git checkout <-new branch name->         (to navigate)
  git checkout -b <-new branch name->      (to create new branch)


  git branch -d <-branch name->            (to delete branch)


  <!-- Merging code -->

  <!-- way1 -->
  way1
  git diff <-branch name->          (to compare commits, branches,
                                     file & more)
  git merge <-branch name->         (to merge 2 branches)

  <!-- way2 -->
  way2
  <!-- PR(Pull request) : It lets you tell others about changes you've pushed to a branch in a repository on Github -->
  create a PR         

<!-- Pull Command -->
<!-- used to fetch and download content from a remote repo and immediately update the local repo to match that content. -->
git pull origin main
  






 
