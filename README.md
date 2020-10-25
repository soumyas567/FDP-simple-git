# FDP-simple-git
A Tutorial Created for teaching Git to Computer science Teachers 

Verison control system (Git)is

    • local and remote reposCreated in 2005 by Linus Torvald
    • Distriuted
    • Cordinates work between developers
    • Keeps track of who  made what change and when
    • Revert back any time	
    • Helps to test your changes without worrying about losing the original
    • Not platform specific
      
Github and big bucket are remote repository Git is the version control System
To work on local repo and push into remote when connected to internet


Features

    • Keeps track of your code history
    • Take snapshot of your files
    • You decide when to take snapshots by commits
    • You can visit any snapshot at any time (safe coding)
    • Stage files before committing
    
Once you make a commit other developers can pull that information to their repository

## To install Git

`sudo apt-get install git` (Linux)
 
http://git-scm.com/download/win  (Download for Windows)

Once you install type the command : 

`git-- version`

Create a folder Git Tutorial,create two python files

`touch print.py`
`touch swap.py`

Add contents to print .py
`print("Hello")`

 Go to the folder create git- init

.git will be created which is a hidden file

git config --global user.name 'soumya somasundaran'
git config --global user.email ‘soumyas567@gmail.com’

git add print.html

git status(To check what happend)

git rm –cached print.py
 git add *.py # All files with .py extension
git add. # add all files


Change contents of print.py

git add .
 
git status	

git commit -m “message” 


git  remote add origin “url of remote repository”

git push -u origin  master

origin is an alias on your system for a particular remote repository. It's not actually a property of that repository.
By doing
git push origin branchname
you're saying to push to the origin repository. There's no requirement to name the remote repository origin: in fact the same repository could have a different alias for another developer.
Remotes are simply an alias that store the url of repositories. You can see what url belongs to each remote by using 
git remote -v

BRANCHES

1.What are branches



1.Create Branch
git branch “branch name” 
2. Checkout branch
git checkout “branch name”
3. Merge new branch in master branch
git merge “branch name”
4. Delete branch
git branch -d “branch name” delete from local
git push origin –delete “branch name”



PULL REQUEST

Owner can share code with others in Github

Others can make changes in that code and send a request to owner to pull/merge his code changes into owners repository



git clone <url> : helps to clone /copy already created repository to local machine
