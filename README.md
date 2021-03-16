# bapractice
# Cheat sheet:
use tab to suggest/fill the command
pwd - prints current working directory
cd - goes to home directory
cd .. - goes up one directory
cd <directory> - goes to that directory
ls - lists contents of current directory
ls -a - lists contents of current directory including hidden files
dir - shows all files
touch <filename> - creates file
nano <filename> - opens nano to edit the file (ctrl X to save + exit)
vim <filename> - opens vim to edit the file (:wq to exit)
echo <string> - prints text to the console
echo <string> > <filename> - prints text into that file
mkdir <directoryname> - creates new directory
cat <filename> - shows contents of file
mv <filename> <location/> - moves file to new location
rm <filename> - deletes file
rmdir <directory> - deletes empty directory
rm -rf <directory> - deletes directory with files inside, -r means recursively, -f means forcefully
clear - clears terminal window

## Git commands
git status - 
git init - initialises repo wherever you are
git add <file> - adds file to staging area for next commit
git add . - adds everything to staging area (all changes)
git commit - commits the change
use git commit -m "" to add a message
git push - push to online destination
git push origin master
can also git push to branch
HEAD - where you last were
git pull - pull changes from online
git clone <url> - clone a repo
git log - shows commit history (exit with q)
git log --oneline - shows log in one line
git remote --v - shows origins/urls, use to check forking etc has worked
git branch <name> - creates new branch
git checkout <branch> - switch to another branch
git checkout -b <name> - creates + switches to new branch
git branch - shows checked out branches
git fetch - look at any changes in the original
git pull - gets changes from the original (can cause merge conflict)
git push -u origin <nameofbranch> - sets branch as upstream - now just use git push
git revert - go back to a previous commit
