# Git basic commands
-------------------
-------------------


* git init
========
Basic comman for initialise Git repository.
this command creates a ".git" hidden folder under the main directory.

* git status
==========
Get status of the Git repository.

* git add
=======
Add files to Git repository for tracking.

-- git add app.js --> single file added.
-- git add . --> all files in directory added.(git add -A)

* git commit
==========
creates a check poit.

-- git commit -m "write your comments here"

* git log
=========
Get all commit information.

* git checkout
=============
View from git repository.

-- git checkout master
-- git checkout <GUID for commits>


# Git Branches
--------------
--------------

-- List all branches
===================
* git branch

-- Adding a branch
================
* git checkout -b <branch-name>

-- Changing branches
==================
* git checkout <branch-name>

-- Merging branch
=================

just move to new branch need merge then type below command

* git merge <branch-name>

eg: (new-branch*):git merge master --> master will be merged to new-branch

-- remove a branch
==================
* git branch -d <branch-name>


Adding to remote repository
============================

* git remote add origin <url>
* git remote add origin https://github.com/shan861/git-notes.git

check origin added as remote use 
* git remote -v

Push or Upload code to remote repository use
* git push -u origin master



