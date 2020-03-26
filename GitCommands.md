# Git Commands
----
### Git Version

`git --version`

---

### Setting up Global Username for the git

`git config –global user.name “Your Name”`

---

### To know the username

`git config user.name`

---

### Set the Email with the Username

`git config –global user.email “Github Email”`

---

### Lists all the usernames with email

`git config –list`

---

### Initiates the repository to a git repository.

`git init`

---

### To know the status of the modifications done

`git status`

---

###  Adds the file or folder for staging

`git add filename`

`git add foldername` 

* For Example: git add src/

---

### Adds multiple files or folders for staging.

`git add filename foldername foldername`	

---

### To un-stage the file for adding more changes into file or to modification

`git rm –cached filename (with file extension)`	

__OR__

`git restore --staged filename`


---

### Adds all to staging

`git add .	`

---

### It keeps/saves the record of all files, lines of code, or any other modifications done with the commit id (for tracking).

`git commit -m “commit message”`

---

### Logs all the detailed history of commits

`git log`

---

### Logs all history of commits in one line.

`git log --oneline`

---

### It goes back to the previous commit.

`git checkout commitid`

`git checkout branchname`

* For Example: git checkout master 

---

### It reverts back to the previous commit from the present commit

`git revert commitid`

---

### It removes all the commits and return to the very initial commit.

`git reset commitid`	

---

### To forcefully remove all commits and does not prompts and no history.

`git reset commitid –hard`

---

### To check/know the present branch.

`git branch`

---

### Takes to the desired branch

`git branch branchname`

---

### To move out from the present branch to the targeted branch

`git checkout branchname`

* For Example: git checkout branchone

---

### To delete the selected branch forcefully (-d is used when it is not merged).

* First be at another branch apart from targeted branch during deletion.

`git branch -d branchname` 

---

### To delete the selected branch forcefully (-D is used when it is merged).

* First be at another branch apart from targeted branch during deletion.

`git branch -D branchname`

---

### It does two things at once, first creates the new branch and shifts on it

`git checkout -b newbranchname`

---

### To merge the branch with the master

* Before merge any branch, we should commit all the changes and then move to the master node.

`git merge branchname`

---

### It shows all the remote git repositories.

`git remote`

### It shows all the remote git repositories with the link.

`git remote -v`

* V stands for verbose

---

### Adds the remote url and pushes on it

`git push remote add origin gitrepourl`

---

### Pushes local repository to the remote repository online at the branch master of remote

`git push origin master`

---

### Pushes forcefully local repository to remote repository online at the branch of master of remote

`git push origin master --force`

---

### Deletes the remote repository mentioned as arguement (remote name) and its URL from its memory

`git remove rm remotename`

---
