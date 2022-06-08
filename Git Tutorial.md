# This is my Git Tutorial

## Seminar 3 Homework

* Repository creation, initialization, commits 

1. To create new repository use *git init*
2. To commit the changes in the file use *git add file_name* and *git commit -m"Message"*
3. To amend the comment use *git commit --amend -m"New message"*

* New branch creation and transition between branches 

1. To create new branch use *git branch branch_name* where branch_name is name of the new branch

2. To swith to branches use *git checkout branch_name* where branch_name is name of 

* Branches merge

1. To merge branches use *git merge branch_name* where branch_name is added to the current branch

* Conflicts at merging and their resolving

1. Conflicts can appear in case contraversal commits are inside the merged branches
2. Git proposes 4 solutions: *Accept current change*, *Accept incoming change*, *Accept both changes*, *Compare changes*.
The most safe is to choose *Accept both change* and munualy delete wrong information
3. After each conflict resolution ise *git add* and *git commit* to fix the result

* Logs
1. To display all commits use *git log*. 
List of all commits with unique ID will be displayed

* Work with remote repositories
1. All work is displayed at GitHub (the account should be created)
2. *git pull* will download the remote repository to your computer
3. *git push* will upload your changes in public repositiry to GitHub
4. *git fork* will make the local copy of the remote repository
5. Steps to make the changes in the remote repository:

 step 1 - *git fork*

 step 2 - *git clone*

 step 3 - create new branch in downloaded repository

 step 4 - make changes in the file at the local computer

 step 5 - *git push* - send the 
 revised file to remote repository

 step 6 - *git request* ask the remote repository owner to accept the changes

 comments

 
