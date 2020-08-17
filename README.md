#This is a readme for a git tutorial

-`git init`: create git repository in current folder
-`git status`: tells you what is going on 

-`git add <FILE>`: places <FILE> into the staging area
-`git commit`: commits files in the staging area
	-if you open this in VI editor do this: push esc then type :q!
	-git config --global core.editor "nano -w"
		-this will make nano your default editor for git

-`git commit -m "MESSAGE"`: one line commit message in 1-step


-`git log`: shows you history 
	-`git log --oneline `: shows you your 1-line versio of history
-'HEAD': tells you where you are looking at

-`git diff`: shows current state with last known state differences
	-New lines are green and deleted lines are red.
	-`git diff --staged`: if you are in the staging area and wants to see the changes with the last commit.
	-can use `git log --oneline ` to specify different versions in histroy

-`git commit -m "MESSAGE"`: this is to do the commit in a short cut


-`git remote add origin <URL>` : adds <URL> with the name origin
-`git push origin master`: pushed the master branch to the origin remote
-`git pull origin master`: pulls the master branch from origin from 

-git remote -v

-You can make changes to different parts of the file and it will combine automatically.
