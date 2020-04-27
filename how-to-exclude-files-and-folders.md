## How to Exclude Files and Folders during Commit and Push

### Situation : Removal of Metadata folders of IDE

For Example - IntelliJ IDEA generates .idea folder
Similarly, it can be applied for Eclipse IDE.

Both the methods work fine!
#### Method 1 : Smarter Way

Steps:
* Locate the local repository of the project in which Git is initialised and if not, initialise it.
* Look for .gitignore file in the same repository.
* Add the filesname or folders names to exclude with their path. <br>
* User wild card character *(* * *)* for multiple files of same file type. <br>
For Example : <br>
.idea <br>
target/ <br>
*.im; <br>
*.iml <br>

* Git will automatically ignore these files and folders from Staging or Commiting or Pushing.
* Proceed with the normal way of Staging, Commiting and Pushing! :)

* To ignore all .a files
  *.a

* but do track lib.a, even though you're ignoring .a files above
  * !lib.a

* only ignore the TODO file in the current directory, not subdir/TODO
  * /TODO

* ignore all files in any directory named build
  * build/

* ignore doc/notes.txt, but not doc/server/arch.txt
  * doc/*.txt

* ignore all .pdf files in the doc/ directory and any of its subdirectories
  * doc/**/*.pdf

#### Method 2 : Traditional Way
Steps:
* First, be in local respository of the project in which Git is initialised and if not, initialise it.

git pull RemoteRepoLink

* git rm -rf folder-name

r stands for Recurrsively

f stands for Forcefully

Example : git rm -rf .idea/

* git commit -m "commit message"
* git remote add origin RemoteRepoLink
* git push -u origin master
