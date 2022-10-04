# **Version control system**

## Glossary

Version contol - also know as "control of original code", is a practice that allows one to monitor all of the chages of the original code and to manage it. 

Repository - is a storage of files supporting versioning.

## General commands in Git
*Getting started:*
* **git --version** - check your current version of Git
* **git init** - initialization of local repository
* **git status** - get info from Git about it's current state

*Adding and commiting:*
* **git add** - add file or files to the next commit
* **git commit -m "message"** - make a commit
* **git log** - shows the history of all our commits with thier hashcodes

*"Surfing" through:*
* **git checkout "hashcode"** - switch between commits. You must write at least 4 starting symbols of hashcode of the commit you wish to switch to. 
* **git checkout master** - return to current state and countinue your work
* **git diff** - check the difference between current file and last commited file

*Creating and working with branches*
* **git branch** - check all the branches 
* **git branch _name_** - create new branch called _name_
* **git checkout _name_** - switch to _name_ branch
* **git merge _branchname_** - merge thr named branch with the current one. This command is usually done from master branch. 
* **git branch -d _name_** - delete specific branch 
* **git checkout -b _branch.hashcode_** - create new branch from the specific commit. Must know it's hashcode.

## Important tips
1. Always put a space after "git" command and the next command
2. Git follows files by <u>names</u>. If the file name is changed, you need to add file with new name + git commit
3. Don't forget to <u>**commit**</u> your progress so you or the other person can track the changes of your file more easily. 
4. Remember:

![In case of fire](01.jpg)

## Additional useful Git commands 