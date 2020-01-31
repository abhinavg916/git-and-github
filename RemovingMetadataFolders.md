# How to Remove Metadata folder of IDE

For Example - IntelliJ IDEA generates .idea folder

Steps:-
1. First, be in local respository of the project in which git is initialised.

git pull RemoteRepoLink

2. git rm -rf folder-name

r stands for Recurrsively

f stands for Forcefully

Example : git rm -rf .idea/

3. git commit -m "commit message"
4. git remote add origin RemoteRepoLink
5. git push -u origin master



Similarly, it can be applied for Eclipse IDE.
