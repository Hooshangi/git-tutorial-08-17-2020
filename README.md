
# This is a very simple git tutorial- VT Lesson- 2020-08-17

## local commands to setup git on your machine
- `git init`: create git repository in current folder
- `git status`: tells you what is going on 

- `git add <FILE>`: places <FILE> into the staging area
- `git commit`: commits files in the staging area
	- if you open this in VI editor, to get out do this--> hit esc button then type :q!
	- git config --global core.editor "nano -w"
		- this will make nano your default editor for git

- `git commit -m "MESSAGE"`: one line commit message in 1-step

- `git log`: shows you history 
	- `git log --oneline `: shows your 1-line version of history
- 'HEAD': tells you where you are looking at

- `git diff`: shows current state with the last known committed state differences
	- New lines are green and deleted lines are red.
	-`git diff --staged`: if you are in the staging area and want to see the changes with the last commit.

## to work with github and remotes

- `git remote add origin <URL>` : adds <URL> with as the origin name origin as the destination
- `git push origin master`: push the master branch to the remoet origin  (push to github)
- `git pull origin master`: pull the master branch from  the remote origin   (pull from github)

- git remote -v

- You can make changes to different parts of the file and it will combine automatically.
- In a merge conflict, look for ">>>" '===' and fix those lines
