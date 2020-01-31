# COMMANDS =>	PURPOSE
----------------------

git --version =>	Git Version

git config –global user.name “your name” =>	Sets global username for the git.

git config user.name =>	To know the username.

git config –global user.email “github email”	=> Sets the email with the username.

git config –list => Lists all the usernames with email.

git init	=> Initiates the repository to a git repository.

git status	=> To know the status of the modifications done.

git add filename (with file extension) OR git add foldername (eg: src/)	=>  Adds the file or folder for staging.

git add filename foldername foldername	=> Adds multiple files or folders for staging.

git rm –cached filename (with file extension)	=> To un-stage the file for adding more changes into file or to modification.

git add .	=> Adds all to staging.

git commit -m “commit message”	=> It keeps/saves the record of all files, lines of code, or any other modifications done with the commit id (for tracking).

git log => Logs all the detailed history of commits .

git log --oneline	=> Logs all history of commits in one line.

git checkout commitid OR git checkout branchname (eg: master) => It goes back to the previous commit.

git revert commitid => It reverts back to the previous commit from the present commit.

git reset commitid	=> It removes all the commits and return to the very initial commit.

git reset commitid –hard	=> To forcefully remove all commits and does not prompts and no history.

git branch	=> To check/know the present branch.

git branch branchname	=> Takes to the desired branch.

git checkout branchname (eg: branch1, master)	=> To move out from the present branch to the targeted branch.

git branch -d branchname	=> To delete the selected branch forcefully (-d is used when it is not merged).
First be at another branch apart from targeted branch during deletion.

git branch -D branchname	=> To delete the selected branch forcefully (-D is used when it is merged).
First be at another branch apart from targeted branch during deletion.

git checkout -b newbranchname	=> It does two things at once, first creates the new branch and shifts on it.

git merge branchname	=> To merge the branch with the master.
Before merge any branch, we should commit all the changes and then move to the master node.

git remote	=> It shows all the remote git repositories.

git remote -v	=> It shows all the remote git repositories with the link.
V stands for verbose

git push remote add origin gitrepourl	=> Adds the remote url and pushes on it.

git push origin master	=> Pushes local repository to the remote repository online at the branch master of remote.

git push origin master --force => Pushes forcefully local repository to remote repository online at the branch of master of remote.

git remove rm remotename => Deletes the remote repository mentioned as arguement (remote name) and its URL from its memory.