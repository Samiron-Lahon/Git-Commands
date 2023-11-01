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
git push  origin main






 
