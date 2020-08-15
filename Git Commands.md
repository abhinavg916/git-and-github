# Git Commands
## Contents
* [Basic Git Setup](#basic-git-setup)
* [Creation of Git Repository](#creation-of-a-git-repository)
* [Staging and Commiting Changes](#staging-and-commiting-changes-in-a-git-repository)
* [Branches in Git](#branches-in-git)
* [Git Remote Repository Setup](#git-remote-repository-setup)
* [Remote to Local Repository Setup](#remote-to-local-repository-setup)

## Basic Git Setup
* To check git version
```
git --version
```
* To setup global username
```
git config –global user.name “Your Name”
```
* To know the username
```
git config user.name
```
* To set the email with the username
```
git config –global user.email “Github Email”
```
* To list all the usernames with their email
```
git config –list
```

## Creation of a Git Repository
* To initiate the git repository
```
git init
```
* To know the status of the modifications done
```
git status
```

## Staging and Commiting Changes in a Git Repository
* To add the file or folder for staging
```
git add filename
git add foldername
```
* To add multiple files or folders for staging at once
```
git add filename foldername foldername
```
* To add all files and folders to staging
```
git add .
```
* To unstage the file from the staging
```
git rm –cached filename	
git restore --staged filename
```
* To commit the changes
```
git commit -m “Commit Message”
```
* To log all the detailed history of commits
```
git log
```
* To log history of commits in short brief (single line)
```
git log --oneline
```
* To go back to the previous commit
```
git checkout commitid
```
* To revert back to the previous commit from the present commit
```
git revert commitid
```
* To remove all the commits and return to the very initial commit
```
git reset commitid
```
* To forcefully remove all commits without any prompts and history
```
git reset commitid –hard
```

## Branches in Git
* To check/know the present branch
```
git branch
```
* To take to the desired branch
```
git branch branchname
```
* To move out from the present branch to the targeted branch
```
git checkout branchname
```
* To delete the selected branch forcefully (-d is used when it is not merged)
    * NOTE: First be at another branch apart from targeted branch during deletion
```
git branch -d branchname
```
* To delete the selected branch forcefully (-D is used when it is merged)
    * NOTE: First be at another branch apart from targeted branch during deletion
```
git branch -D branchname
```
* To create new branch
    * NOTE: It does two things at once, first creates the new branch and shifts on it
```
git checkout -b newbranchname
```
* To merge the branch with the master
    * NOTE: Before merge any branch, we should commit all the changes and then move to the master node
```
git merge branchname
```

## Git Remote Repository Setup
* To show all the remote git repositories
```
git remote
```
* To show all the remote git repositories with the link
    * NOTE: `v` stands for verbose
```
git remote -v
```
* To pdd the remote URL and push on it
```
git push remote add origin gitrepourl
```
* Switching remote URL's and push on it
   * Check current URL  `git remote -v`
   * Change your remote's URL from HTTPS to SSH by `git remote set-url origin gitRepoURL`
   * Verify that the remote URL has changed `git remote -v`
* To push local repository to the remote repository online at the branch master of remote
```
git push origin master
```
* To push forcefully local repository to remote repository online at the branch of master of remote
```
git push origin master --force
```
* To delete the remote repository mentioned as arguement (remote name) and its URL from its memory
```
git remove rm remotename
```
* To push instantly (when origin is already set)
```
git push
```

## Remote to Local Repository Setup
* To clone the remote repository to the local machine
```
git clone URL
```
* To update the remote changes into the local repository
```
git pull
```
